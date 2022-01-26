<template>
           <nav class="navbar nav-bar navbar-expand-lg fixed-top">
            <a href="" class="navbar-brand brand">Davies Adventure</a>

            <button class="navbar-toggler" type="button"
			data-toggle="collapse"
			data-target="#toggleMobileMenu"
			aria-control shadow-nones="#toggleMobileMenu"
			aria-expanded="false"
			aria-label="Toggle navigation">
				<span class="oi oi-menu"><i class="fa fa-bars"></i></span>
			</button>
            <div class="collapse navbar-collapse " id="toggleMobileMenu">
            <ul class="navbar-nav ml-auto text-center ms-auto">
                <li class="nav-item">
                    <router-link to="/" class="nav-link">Home</router-link>
                </li>

                <li class="nav-item">
                    <router-link to="/about" class="nav-link">About</router-link>
                </li>

                <li class="nav-item">
                    <router-link to="/contact" class="nav-link">Contact Us</router-link>
                </li>

                <li class="nav-item">
                    <router-link to="/login" class="nav-link">Login</router-link>
                </li>	
                </ul>
            </div>

        </nav>
</template>