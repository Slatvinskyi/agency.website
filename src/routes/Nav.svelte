<div>
		<!-- Navbar goes here -->
		<nav class="bg-gradient-to-r from-yellow-300 via-yellow-200 to-yellow-700 shadow-lg">
			<div class="max-w-6xl mx-auto px-4">
				<div class="flex justify-between">
					<div class="flex space-x-7">
						<div>
							<!-- Website Logo -->
							<a href="/" class="flex items-center py-4 px-2">
								
								<svg class="h-12 w-12 mr-2" xmlns="http://www.w3.org/2000/svg" width="36" height="36" viewBox="0 0 24 24"><path d="M18.586 10.081c-1.439 0-1.35 2.802-2.029 4.071-.114.211-.425.184-.5-.044-.771-2.364-.419-8.108-2.51-8.108-2.189 0-1.648 7.433-2.5 10.462-.063.23-.381.25-.474.028-.9-2.161-.799-6.875-2.502-6.875-1.762 0-1.612 3.949-2.302 5.54-.091.213-.392.22-.493.01-.503-1.049-.664-3.165-2.564-3.165h-2.213c-.275 0-.499.224-.499.499s.224.501.499.501h2.213c1.572 0 1.038 3.484 2.854 3.484 1.684 0 1.502-3.79 2.223-5.47.088-.208.382-.202.466.006.805 2.047.79 6.98 2.641 6.98 2.077 0 1.337-7.856 2.443-10.621.083-.211.384-.222.479-.012 1.029 2.25.487 8.126 2.344 8.126 1.639 0 1.737-2.706 2.23-4.038.081-.212.373-.227.474-.027.516 1.001.846 2.572 2.4 2.572h2.235c.275 0 .499-.224.499-.499 0-.276-.224-.5-.499-.5h-2.235c-1.323 0-1.117-2.92-2.68-2.92z"/></svg>
								<span class="font-semibold text-white text-lg">logo</span>
							</a>
						</div>
						<!-- Primary Navbar items-->
						<div class="hidden md:flex items-center space-x-3">
							<a href="/" class="py-4 px-2 text-white font-semibold hover:text-black transition duration-300">Home</a>
							<a href="services" class="py-4 px-2 text-white font-semibold hover:text-black transition duration-300">Services</a>
							<a href="about" class="py-4 px-2 text-white font-semibold hover:text-black transition duration-300">About</a>
							<a href="contact" class="py-4 px-2 text-white font-semibold hover:text-black transition duration-300">Contact Us</a>
						</div>
					</div>
					<!-- Secondary Navbar items 
					<div class="hidden md:flex items-center space-x-3 ">
						<a href="" class="py-2 px-2 font-medium text-gray-500 rounded hover:bg-green-500 hover:text-white transition duration-300">Log In</a>
						<a href="" class="py-2 px-2 font-medium text-white bg-green-500 rounded hover:bg-green-400 transition duration-300">Sign Up</a>
					</div>-->
					<!-- Mobile menu button -->
					<div class="md:hidden flex items-center">
						<button class="outline-none mobile-menu-button">
						<svg class=" w-6 h-6 text-white hover:text-black"
							x-show="!showMenu"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							viewBox="0 0 24 24"
							stroke="currentColor">
							<path d="M4 6h16M4 12h16M4 18h16"></path>
						</svg>
					</button>
					</div>
				</div>
			</div>
			<!-- mobile menu -->
			<div class="hidden mobile-menu">
				<ul class="">
					<li class="active"><a href="/" class="text-white block text-sm px-2 py-4 hover:bg-black transition duration-300">Home</a></li>
					<li><a href="services" class="text-white block text-sm px-2 py-4 hover:bg-black transition duration-300">Services</a></li>
					<li><a href="about" class="text-white block text-sm px-2 py-4 hover:bg-black transition duration-300">About</a></li>
					<li><a href="contact" class="text-white block text-sm px-2 py-4 hover:bg-black transition duration-300">Contact Us</a></li>
				</ul>
			</div>

            <script>
                const btn = document.querySelector("button.mobile-menu-button");
                const menu = document.querySelector(".mobile-menu");
        
                btn.addEventListener("click", () => {
                    menu.classList.toggle("hidden");
                });
            </script>
			
		</nav>
		<!--<h1 class="text-green-500 text-2xl md:text-3xl lg:text-4xl font-bold p-4"></h1>-->
	</div>
