<!DOCTYPE html>
<html>

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<link rel="stylesheet" href="https://cdnjs.
	cloudflare.com/ajax/libs/font-awesome/4.7.0/
	css/font-awesome.min.css">
	<title>Healtybee</title>
	<link rel="stylesheet" href="style.css">
	
	<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Verdana, Geneva, Tahoma, sans-serif;

}

.container {
    background: url("undraw_yoga_248n.svg");
    background-repeat: no-repeat;
    background-position: right;
    background-color: #6159e5;
    height: 100vh;
    width: 100%;

}

nav {
    font-size: 1.3rem;
}

ul {
    list-style: none;
}

ul li {
    display: inline-block;
    margin: 15px 0 0 65px;
    position: relative;

}

ul li a {
    text-decoration: none;
    color: snow;
    font-size: 35px;

}

ul li a:active{
    color: black;
}

ul li::after {
    content: "";
    background: snow;
    height: 5px;
    width: 0%;
    position: absolute;
    left: 0;
    bottom: -10px;
    transition: .4s ease;

}

ul li:hover::after {
    width: 100%;
}

.text {
    color: white;
    position: absolute;
    top: 30%;
    left: 5%;

}

h1 {
    font-size: 5rem;
    color: snow;
}

p {
    font-size: 18px;
    padding: 10px;
    margin-top: 25px;
    line-height: 2;
}



button {
    width: 500px;
    padding: 15px;
    text-align: center;
    border-radius: 50px;
    border: 2px solid snow;
    background: transparent;
    color: white;
    position: relative;
    overflow: hidden;
    z-index: 3;
    margin-top: 30px;
    font-size: 35px;
    display: block;

}

.btn::after {
    content: "";
    background: snow;
    width: 0;
    height: 100%;
    position: absolute;
    left: 0;
    bottom: 0;
    transition: 0.4s;
    z-index: -1;
}

.btn:hover::after {
    width: 100%;

}

.btn:hover {
    color: #6159e5;
    border: hidden;
}

.containersec {

    height: 100%;
    width: 100%;


}

.imglogo img {
    height: 100vh;
    width: 40%;
    float: left;
    background-color: #6159e5;

}

.textsec {
    background-color: rgba(97, 89, 229);
    width: 60%;
    height: 100vh;
    float: right;

}

.services {
    display: inline-block;
    background-color: #6159e5;

}

.services img {
    float: left;
    width: 30%;
    height: 400px;
    margin: 20px 25px;
    border: 1px solid transparent;
    border-radius: 10px;
    box-shadow: 10px 10px 100px #585858;
    background-color: snow;

}

.newbutton {
    margin: 50px 200px;

}

#newh1 {
    margin: 50px 220px;
    position: relative;
}

.icons ul li {
    position: relative;
    color: snow;


}

.icons {
    background-color: #6159e5;
    height: 100px;
    width: 100%;


}

.icons ul{
        display: inline-block;
        position: absolute;
        right: 30px;
        padding-top: 15px;
}
span{
    font-size: 30px;
    color: snow;
    display: inline-block;
    PADDING: 30px 20px;
   
}

#heading{position: relative;
    margin-left: 50px;
    margin: 40px;
}
#heading::after{
    content: "";
    background-color: snow;
    width: 100px;
    height: 4px;
    position: absolute;
    left: 3px;
    bottom: -15px;
}


#newh1::after{

    content: "";
    background-color: snow;
    width: 130px;
    height: 4px;
    position: absolute;
    left: 8px;
    bottom: -10px;
}
hr
	</style>
</head>

<body>
	<div class="container">
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#check">Why US</a></li>
				<li><a href="#serv">Services</a></li>
				<li><a href="#icons">Follow ON</a></li>
			</ul>
		</nav>
		<div class="text">
			<h1>WELCOME TO<br>HEALTHYBEE</h1>
			<p>Lorem ipsum is a placeholder text commonly
				used to <br>demonstrate the visual form of a
				document <br>or a typeface without relying.</p>

			<button type="button" class="btn">Read More</button>
		</div>

	</div>
	<hr>
	<div class="containersec" id="check">
		<div class="imglogo">
			<img src="undraw_mindfulness_scgo.svg" alt="">
		</div>
		<div class="textsec">
			<h1 id="newh1">WHY US?</h1>
			<div class="newbutton">

				<button type="button" class="btn">What We Provide?</button>
				<button type="button" class="btn">FEE & Charges</button>
				<button type="button" class="btn">OUR Acheviments</button>
				<button type="button" class="btn">Faculties</button>
				<button type="button" class="btn">Checking</button>
				<h2></h2>

			</div>

		</div>

	</div>
<hr>
	<div class="services" id="serv">
		<h1 id="heading">OUR Services</h1>
		<img src="undraw_Activity_tracker_re_2lvv.svg" alt="">
		<img src="undraw_personal_training_0dqn.svg" alt="">
		<img src="undraw_fitness_stats_sht6 (1).svg" alt="">
		<img src="undraw_fitness_tracker_3033.svg" alt="">
		<img src="undraw_personal_trainer_ote3.svg" alt="">

		<img src="undraw_Private_data_re_4eab.svg" alt="">

	</div>
	</div>
	<div class="icons">
	<span>HEALTHYBEE, Copyright &copy; 2021</span>
		<ul id="icons">
			<li><a href="https://www.facebook.com">
					<i class="fa fa-facebook" aria-hidden="true"></i>
				</a></li>

			<li><a href="https://www.twitter.com">
					<i class="fa fa-twitter" aria-hidden="true"></i>
				</a></li>

			<li><a href="https://www.instagram.com">
					<i class="fa fa-instagram" aria-hidden="true"></i>
				</a></li>

			<li><a href="https://www.linkein.com">
					<i class="fa fa-linkedin" aria-hidden="true"></i>
				</a></li>
		</ul>
	</div>
</body>
