- Referencias
	- [backpressure](https://medium.com/@jayphelps/backpressure-explained-the-flow-of-data-through-software-2350b3e77ce7)
	- [Why Netflix Needed to Create Failure](https://www.gremlin.com/chaos-monkey/the-origin-of-chaos-monkey/)
- How to get the current user login
	- ```java
	  public Mono<TareaDTO> save(TareaDTO tareaDTO) {
	      log.debug("Request to save Tarea : {}", tareaDTO);
	      return SecurityUtils
	              .getCurrentUserLogin()
	              .switchIfEmpty(Mono.just("sys.admin"))
	              .map(usuario -> tareaMapper.toEntity(tareaDTO.usuario(usuario)))
	              .flatMap(tareaRepository::save)
	              .map(tareaMapper::toDto);
	     }
	  ```