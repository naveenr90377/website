# website
my firstgithub program
<!DOCTYPE html>
<html lang="en">
<head>
	<link href=
"://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
	rel="stylesheet"
	/>
</head>

<body>
	<!-- NAVBAR -->
	<nav class="navbar navbar-expand
				navbar-dark bg-success">
	<div class="container-fluid">
		<a class="navbar-brand" href="./">
		space-wikipedia
		</a>
		<ul class="navbar-nav me-auto mb-2 mb-lg-0">
			
		<!-- NAVBAR LINKS -->
		<li class="nav-item">
			<a class="nav-link active" href="#">
			About Us
			</a>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#">
			Contact
			</a>
		</li>
			
		<!--DROPDOWN -->
		<li class="nav-item dropdown">
			<a
			class="nav-link dropdown-toggle"
			href="#"
			id="navbarDropdown"
			role="button"
			data-bs-toggle="dropdown"
			>
			Coding Articles
			</a>
			<!-- DROPDOWN OPTIONS -->
			<ul class="dropdown-menu">
			<li>
				<a class="dropdown-item" href="#">
				Page 1
				</a>
			</li>
			<li>
				<a class="dropdown-item" href="#">
				Page 2
				</a>
			</li>
			</ul>
		</li>
		</ul>
		<!-- SEARCH BOX -->
		<form class="d-flex">
		<input
			class="form-control me-2"
			type="search"
			placeholder="Search site"
		/>
		<button class="btn btn-primary" type="submit">
			Search
		</button>
		</form>
	</div>
	</nav>

	<!-- ARTICLE -->
	<div class="container mt-5">
	<div class="row">
		<div class="col-sm-2">Author Name</div>
		<div class="col-sm-8">
		<h2>Article Title</h2>
		<h5>Created on 20 Jan 2022</h5>
			
		<!-- ARTICLE TEXT -->
			
<p>
		NASA’s future will continue to be a story of human exploration, technology, and science. We will go back to the Moon to learn more about what it will take to support human exploration to Mars and beyond. We will continue to nurture the development of a vibrant low-Earth orbit economy that builds on the work done to date by the International Space Station. NASA engineers will develop new technologies to improve air transport at home and meet the challenges of advanced space exploration. Our scientists will work to increase an understanding of our planet and our place in the universe. We will continue to try to answer the question, “Are we alone?”

Unlike the way the space program started, NASA will not be racing a competitor. Rather, we will build upon the community of industrial, international, and academic partnerships forged for the space station. Commercial companies will play an increasing role in the space industry: launching rockets and satellites, transporting cargo and crew, building infrastructure in low-Earth orbit. NASA will continue to be a global leader in scientific discovery, fostering opportunities to turn new knowledge into things that improve life here on Earth.


		</p>

		</div>
	</div>

	<!-- FORM -->
	<form class="was-validated">
		<!-- Email Address Input -->
		<div class="mb-3">
		<label for="email" class="form-label">
			Email Address:
		</label>
		<input
			type="email"
			class="form-control"
			id="email"
			placeholder="Enter your email id"
			required
		/>
		<div class="valid-feedback">
			Valid Email id
		</div>
		<div class="invalid-feedback">
			Please fill out this field.
		</div>
		</div>
		<!-- Password Input -->
		<div class="mb-3">
		<label for="password" class="form-label">
			Password:
		</label>
		<input
			type="password"
			class="form-control"
			id="password"
			placeholder="Enter your password"
			minlength="8"
			required
		/>
		<div class="form-text" id="password-help-block">
			Password needs to be 8 characters long.
		</div>
		<div class="valid-feedback">
			Valid Password.
		</div>
		<div class="invalid-feedback">
			Please fill out this field.
		</div>
		</div>
		<!-- Checkbox -->
		<div class="form-check mb-3">
		<input
			class="form-check-input"
			type="checkbox"
			id="checkbox"
			required
		/>
		<label class="form-check-label" for="checkbox">
			I agree on T & C.
		</label>
		<div class="valid-feedback">
			You Agree to the T & C.
		</div>
		<div class="invalid-feedback">
			Check this checkbox to continue.
		</div>
		</div>
		<button type="submit" class="btn btn-primary">
		Submit
		</button>
	</form>
	</div>

	<script src=
"https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js">
	</script>
</body>
</html>
