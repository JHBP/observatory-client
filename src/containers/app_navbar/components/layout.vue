<template>
	<nav class="navbar navbar-expand-lg navbar-light bg-light">
	  <a class="navbar-brand" href="/#/">RCOS</a>
	  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
	    <span class="navbar-toggler-icon"></span>
	  </button>

	  <div class="collapse navbar-collapse" id="navbarSupportedContent">
	    <ul class="navbar-nav mr-auto">
	      <li class="nav-item">
          <a class="nav-link" href="/#/projects">Projects</a>
        </li>

        <li class="nav-item">
          <a class="nav-link" href="/#/users">Users</a>
        </li>

        <li class="nav-item">
          <a class="nav-link" href="/#/achievements">Achievements</a>
        </li>

        <li>
          <a class="nav-link" href="/#/blogs">Blogs</a>
        </li>

        <li>
          <a class="nav-link" href="/#/attend">Attend</a>
        </li>

        <li>
          <a class="nav-link" href="/#/mentor/verify">Verify</a>
        </li>

        <li>
          <a class="nav-link" href="/#/mentor/small_group">Small Group</a>
        </li>

	    </ul>

	    <ul class="navbar-nav ml-auto">
	      <li class="nav-item">
	        <a class="nav-link" href="/#/auth/register">Register</a>
	      </li>
	      <li class="nav-item">
	        <a class="nav-link" href="/#/auth/login">Login</a>
	      </li>
	    </ul>
	  </div>
	</nav>
</template>

<script>
// TODO - this should be split into a series of smaller components
export default {
  name: 'Navbar'
}
</script>
