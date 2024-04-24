# -<!DOCTYPE html>

<!--Header-->
<html>
	<head>
		<meta charset="UTF-8">
		<meta name="description" content="Newbie Restaurant">
		<meta name="viewport" content="width=device, initial-scale=1.0">
			<title>Newbie Restaurant</title>
			<link rel="icon" type="imgae/png" href="http://t3.gstatic.com/images?q=tbn:ANd9GcQ8A7ixWCUhPbizhcP2j8rmPkKgDgJDKb_2AYiGlTEkRp4gnuVcKoNRxCTKjcf-GRp0_L5a3aT-M6r05tYNhAA" sizes="16x16">
			<link rel="stylesheet" href="style.css">		
	</head>

<body>
		<link rel='stylesheet' type='text/css' href='css/style.css' />
<style>
	body {
		background-image:url("https://st2.depositphotos.com/1891407/10272/v/950/depositphotos_102723300-stock-illustration-cooking-kitchen-food-background.jpg");
		background-color: #ccc;
		background-position: center;
		background-repeat: repeat;
		background-size: cover;
	}
	</style>
	<style type="text/css">
	body {
		background-color: black;
		color: yellow;
	}
	</style>
	<table style="width:80%">
	</style>
	<table style="float:left">
	</style>
<center>
	<header>
			
		<h1>
			<img src="http://t3.gstatic.com/images?q=tbn:ANd9GcQ8A7ixWCUhPbizhcP2j8rmPkKgDgJDKb_2AYiGlTEkRp4gnuVcKoNRxCTKjcf-GRp0_L5a3aT-M6r05tYNhAA" width="100" height="100" alt="Header logo" style="vertical-align:middle;margin:50px 0px">Newbie Restaurant
		</h1>
		
			<a href="main.php"><button>< Back</button></a>
			<a href="login.php"><button type="button">Login / Sign Up</button></a>

<hr/>

	<a href="#deals"><button>Deals</button></a>
	<a href="#main"><button>Main Dish</button></a>
	<a href="#side"><button>Side Dish</button></a>
	<a href="#drinks"><button>Drinks</button></a>
	<a href="order.php"><button>Cart</button></a>
	
	<h2>Menu</h2>
	
<table id="deals">
		<thead><h3 id="deals">Deals</h3></thead>
				<tr>
					<th></th>
					<th>Name</th>
					<th>Price</th>
					<th>Preference</th>
					<th></th>
				</tr>
			<tbody id="burgerdeal">
				<tr>
					<td><img src="https://bluejeanchef.com/uploads/2019/08/Potato-Salad-1280-2578-819x1024.jpg" width="200" height="150" alt="Burger, Salad and Drinks"></td>
					<td width="100">Smoked Burger +  Potato Salad + Soft Drinks / Fruit Juice</td>
					<td>RM 21.00</td>
					<td>
						
							<ul>
								<li>Burgers are allowed to choose from Chicken, Beef and Fish</li>
								<li>Drinks are allowed to choose from Soft Drinks / Fruit Juice</li>
							</ul>
						
					</td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
				</tr>
			</tbody>
			<tbody id="beefdeal">
				<tr>
					<td><img src="https://cdn.concreteplayground.com/content/uploads/2017/06/IMG_7593-e1497238635359.jpg" width="200" height="150" alt="Beef, Taco and Drinks"></td>
					<td>Beef Wellington + American Style Tacos + Soft Drinks / Fruit Juice</td>
					<td>RM 25.00</td>
					<td>
						<ul>
							<li>Drinks are allowed to choose from Soft Drinks / Fruit Juice</li>
						</ul>
					</td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
				</tr>
			</tbody>
			<tbody id="pizzadeal">
				<tr>
					<td><img src="https://img.hellofresh.com/f_auto,fl_lossy,q_auto,w_1200/hellofresh_s3/image/super-cheesy-pizza-7fdf4215.jpg" width="200" height="150" alt="Pizza, Wedges and Drinks"></td>
					<td>Chicago Deep Dish Pizza + Crispy Roast Potatoes + Soft Drinks / Fruit Juice</td>
					<td>RM 24.00</td>
					<td>
						<ul>
							<li>Drinks are allowed to choose from Soft Drinks / Fruit Juice</li>
						</ul>
					</td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
				</tr>	
			</tbody>	
</table>

<hr/>

<table width=200 cellpadding=10>
		<thead><h3 id="main">Main Dish</h3></thead>
		<style>
		<style table="main dish">
		tr:nth-child(even) {
				background-color: black;
				}
		td {
			padding: 15px;
			text-align:center
		}
		table {
			width: 100%
		}
		<!--div.table {
			position: relative;
			width: 400px;
			height: 200px;
			border: 3px solid red;
			}-->
			</style>
		<!--div.table {
			position: relative;
			width: 400px;
			height: 200px;
			border: 3px solid red;
			}-->
		</style>
			<tr>
					<th></th>
					<th>Name</th>
					<th>Price</th>
					<th>Preference</th>
					<th></th>
			</tr>
			<tr>
				<tbody id="burger">
					<td><img src="https://cdn.discordapp.com/attachments/590915592526102576/753153304846008360/08c818739e4b48ce96d319c16f4cc0ca.jpg" width="200" height="150" alt="Smoked Burger"></td>
					<td>Smoked Burger</td>
					<td>RM 7.00</td>
					<td style="white-space:nowrap">
						<ul>
							<li>Chicken</li>
							<li>Beef</li>
							<li>Fish</li>
						</ul>
					</td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
				</tbody>
			</tr>
			<tr>
				<tbody id="beef">
					<td><img src="https://cdn.discordapp.com/attachments/590915592526102576/753155665912135710/unnamed.jpg" width="200" height="150" alt="Beef Wellington"></td>
					<td>Beef Wellington</td>
					<td>RM 7.00</td>
					<td style="white-space:nowrap">
						<ul>
							<li>Mushroom sauce</li>
							<li>BBQ sauce</li>					
						</ul>
					</td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
				</tbody>
			</tr>
			<tr>
					<td><img src="https://cdn.discordapp.com/attachments/590915592526102576/753158706870616114/chicago-deep-dish-pizza.jpg" width="200" height="150" alt="Chicago Deep Dish Pizza"></td>
					<td>Chicago Deep Dish Pizza</td>
					<td>RM 7.00</td>
					<td></td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
			</tr>
			<tr>
				<tbody id="appie">
					<td><img src="https://cdn.discordapp.com/attachments/590915592526102576/753158096540401694/iStock-450752471_1.jpg" width="200" height="150" alt="Apple Pie"></td>
					<td>Apple Pie</td>
					<td>RM 7.00</td>
					<td></td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
				</tbody>
			</tr>
			<tr>
					<td><img src="https://cdn.discordapp.com/attachments/590915592526102576/753160516582506507/fc79hi070-01-main.png" width="200" height="150" alt="Berrys Pie"></td>
					<td>Berrys Pie</td>
					<td>RM 7.00</td>
					<td></td>
					<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
			</tr>
</table>

<hr/>

<table>
		<thead><h3 id="side">Side Dish</h3>
			<tr>
				<th></th>
				<th>Name</th>
				<th>Price</th>
				<th>Preference</th>
				<th></th>
			</tr>
			<tr>
				<td><img src="https://servethiswiththat.com/wp-content/uploads/2018/04/american-style-tacos-677px.jpg.png" width="200" height="150" alt="American Style Tacos"></td>
				<td>American Style Tacos</td>
				<td>RM 7.00</td>
				<td></td>
				<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
			</tr>
			<tr>
				<td><img src="https://www.seriouseats.com/recipes/images/2016/12/20161201-crispy-roast-potatoes-29-625x469.jpg" width="200" height="150" alt="Crispy Roast Potatoes"></td>
				<td>Crispy Roast Potatoes</td>
				<td>RM 7.00</td>
				<td></td>
				<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
			</tr>
			<tr>
				<td><img src="https://hips.hearstapps.com/hmg-prod/images/190411-potato-salad-horizontal-1-1555688422.png" width="200" height="150" alt="Potato Salad"></td>
				<td>Potato Salad</td>
				<td>RM 7.00</td>
				<td></td>
				<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
			</tr>
</table>

<hr/>

<table>
		<thead><h3 id="drinks">Drinks</h3></thead>
			<tr>
				<th></th>
				<th>Name</th>
				<th>Price</th>
				<th>Preference</th>
				<th></th>
			</tr>
			<tr>
				<td><img src="https://cdn-a.william-reed.com/var/wrbm_gb_food_pharma/storage/images/publications/food-beverage-nutrition/foodnavigator-asia.com/article/2018/03/29/soft-drink-health-concerns-not-yet-trickled-down-into-social-media-users-mentions-of-brands/7819019-1-eng-GB/Soft-drink-health-concerns-not-yet-trickled-down-into-social-media-users-mentions-of-brands.jpg" width="200" height="150" alt="Soft Drinks"></td>
				<td>Soft Drinks</td>
				<td>RM 7.00</td>
				<td>
					<ul>
						<li>Pepsi</li>
						<li>Cola</li>
						<li>Sprite</li>
						<li>Fanta</li>
					</ul>
				</td>
				<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
			</tr>
			<tr>
				<td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRnPHDOyWzAT5OORcc3TzGB2u6bJWM8rFA1pw&usqp=CAU" width="200" height="150" alt="Fruit Juice"></td>
				<td>Fruit Juice</td>
				<td>RM 7.00</td>
				<td>
					<ul>
						<li>Watermelon Juice</li>
						<li>Orange Juice</li>
						<li>Apple Juice</li>
						<li>Passion Fruit Juice</li>
					</ul>
				</td>
				<td><a href="login.php"><button type="button">Add to Cart</button></a></td>
			</tr>
</table>

<hr/>

<a href="order.php"><button type="button">View Order</button></a>

<hr/>

</body>

<footer>

<center> 
	
	<table>
		<thead><h3>Contact Us:</h3></thead>
			<tr>
				<td>Email: newbierestaurant@hotmail.com</td>				
			</tr>
			<tr>
				<td>Hotline: +123456789</td>
			</tr>
	</table>		
		
	<table>
		<thead><h3>Find us on Social Media:</h3></thead>
			<tr>
				<td><a href="https://www.instagram.com/newbienewmarket/?hl=en"><img src="data:image/jpeg;base64,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" width="50" height="50"></a></td>
				<td><a href="https://www.facebook.com/restaurantnewbies/"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAmVBMVEU7WZj///9DYJtJZZ4/Xps3VZb3+PspTJGYpccxUZNIYp2/yd3d4uxjeavY3ek9XJtQbKUwUZdzh69ofarz9ffI0dqClrVbdaUlSY+vutLr7vWBkrrP1+aqttFWbqUoS5Dg5emZqcDCytfj5+2Onrx6jrK1wM9whrWNnsPT2ebHz+GgrswfRY53jLhrf6+jr8uOoLu5w9JdeKa56c0yAAAEzklEQVR4nO3daXeiMBSA4aAECFuhat3tYhdAbWfm//+40Vo7c860cCWG5Gbu+2E+zGmR54RFClHmfHR3P8jCsG9DYZgNftydYOz9X290LXLO7Inn+eDB+yNcP3KrfO8JcROfhPG10L06ShKD0VG4thR4IMYHofdoK3BPfBruhSPr9sC/Es97obXb6CE+9tidzUDG/BG7z3WvhNLyGzaweTc8bKasr3sdFNdnPd2roLie9UKXhOgjIf5IiD8S4o+E+CMh/kiIPxLij4T4QyDkp9r9usFCLvzbya0vxNEnuBC+Pzl2/G/QYgwV8j2FZy/FMqrKNH4vTcvFooqi6XITFLuXJAuZ2P9Q46JMFPLJliebaubU5nmzdRqFjUTzhEJkReXV6/6UNd51MUzIRTiPwLz9QCITcr4qFnAeOiEXWVCe5XNwbaWCz+G7H8Yx9PvThoMncuEkSc8eQFTC7a6Nz0GzH/Jt0RKIZAx5/tbOh2UMOd+0HEEkY8h5MGw9hDiE8xZnic8QCEUSSwARjCHvRRJADEIRyAARCEXW+jB6zHjhVmobRTCGfiIHNH8M/fOud/GNof8iO4SmC0UlKzR8KxWJzLsZDGPoLyVPFaYLeZjKAg0X+jvpjdTw/TBfygONHkMeyp4MD5ksFK8yl00ohMUZl/bebH24v/ZPZd9gIZ+CeXH1Nk+y0L36t+bX0SbkLvSyogwS5vu54F/V/ELahGIFO9AM31a+kJnWo08IO9DMCiY580yfEPQnNi9o+wjGZ/qEoD/kR0x63pm+I80GAIxf5SdH6hNC3rNF0tuozvMh4HQ4LHz519El5C5AuE4uMINXnxBwwk/dC8xv1SYMAcLqEpOwjRZOL7AbGi30ltYLN7cXeCWjhYH1Y0hCUCRUFQlJCI+EqiIhCeGRUFUkJCE8EqqKhCSER0JVWSIU3+dfQYTbmiW8p1noJjW9Nj+X6C1XdUvYLyPRKxTjuC7AsyaztHYJcVwBNmOVQulHnBtbbG0XLq0XFhPbhTvr90PIPWLUQsDTpciFaxewGqiFC8htftTCqeZ3beqFG+uFhfXCne1CL7H9SDNb2S4s+7YLI8gJH7VwCloNzMIN6MlFzMLCdqE3Bz2ciVg4gz3mjliYjm3fSqvMdmHUs10IOx1iFsJOh4iFHujqELNwBjsdIhaugbO+8ApL0PUvZmEFujrELIyu9AtXX82g/wxyh7T8/tfjADjrS+l9/K8m0B9zGehJhfzbJbig63vlwi9n0H98wjrgk+i8YFKzBCOENVnytElNJCQhPBKqioQkhEdCVZGQhPBIqCoSkhAeCVVFQhLCI6GqSEhCeCRUFQlJCI+EqiIhCeGRUFUkJCE8EqqKhCSER0JVkZCE8EioKhKSEB4JVUVCEsIjoapISEJ4JFQVCUkIj4SqIiEJ4ZFQVSQkITwSqoqEJIT3Pwj7F1jK+XUnDNmvC3xv8vl1JuQr9iOXX0yLF+5KmN+w1G6h/8CcgY7NtCshz4bMebBZmD87zBk+XeIrzM+sI6G4Hu6FTjzontiNMB+XzkHolN0TOxGK8YNzFDrxk+h4Z+xAyPPr1DkJneHP8STvEgkTtv/2eC4mq+fjx4mx0+JGj7/6vc5ys8jxmgp428X3xzcj70P2G0SvfjFQUs1EAAAAAElFTkSuQmCC" width="50" height="50"></a></td>
				<td><a href="https://x.com/thefoodienewbie?lang=en"><img src="data:image/png;base64,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" width="50" height="50"></a></td>
			</tr>
	</table>

</footer>


</html>
