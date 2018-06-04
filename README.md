<h1> Uso </h1>

<h2> Obtener una instancia de la librería </h2>
<p> 
	<i> RemoteSourceModule.getInstance().getRemoteSource() </i> <br>
	Con esta operación obtenemos una instancia de la librería.
</p>

<h2> Obtener una definición a partir de un término </h2>
<p> 
	<i> instanciaAPI.getMeaning(term) </i> <br>
	Con esta operación se obtendrá un String con el resultado de buscar term en la Wikipedia. Tener en cuenta que instanciaAPI es la instancia conseguida en la operación anterior.
	La operación podría lanzar la excepción IOException en caso de que ocurra un error.
</p>

