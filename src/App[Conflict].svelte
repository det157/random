<script>
	import { AvatarGenerator } from 'random-avatar-generator';
	const generator = new AvatarGenerator();

	var avatar = generator.generateRandomAvatar();

	//Random number generator, in range
	function getRandomArbitrary(min, max) {
  return Math.round(Math.random() * (max - min) + min);
}

	var cellPhone = getRandomArbitrary(23,225)
	var carInsurance = getRandomArbitrary(75,220)
	var carPayment = getRandomArbitrary(70,520)
	var cableInternet = getRandomArbitrary(70,170)

	//Names
	var names = ['Zi Hurley','Javan Avalos','Marcus Johnson','Rianne Mill','Penny Valenzuela','Kayne Emery','Leilani Read','Mercedes Ochoa','Freyja Oconnor','Trinity Redfern','Mikaela O\'Gallagher','Kenneth Downs','Miriam Begum','Hawwa Mellor','Joy Zuniga','Abdur-Rahman Mccallum','Kairo Kidd','Renae Casey','Klay Merrill','Sian Rudd','Nolan Wolfe','Edie Walters','Isobel Black','Jokubas Goldsmith','Keenan Busby','Linda Trejo','Ismael Turner','Tj Mcnamara','Bob Nichols','Maaria Rayner','Iain Forbes','Jon-Paul Horn','Etta Patton','Kirstin Howell','Alessandra Maddox','Marisa Sharples','Nadia Ellison','John Chung','Ammarah Bray','Corrina Gill','Joanne Howard','Samira Zavala','Kezia Rivera','Bernard Odom','Yolanda Cash','Lennie Pollard','Lily Pham','Nicolas Henry','Kobi English','Charley Howells','Rio Schmitt','Joseff Nieves','Arielle Ray','Cecelia Sheppard','Paris Carty','Karan Rivas','Eshan Gaines','Austin Storey','Kimberly Wiggins','Lydia Davila','Aarush Markham','Tamera Knights','Amber-Rose Avery','Kie Gibbs','Donnell Hilton','Aliya Wormald','Sahil Armstrong','Rafferty Garrison','Simone Williamson','Vincenzo Mathews','Bethany Pratt','Merlin Perez','Tasmin Ferrell','Indigo Petty','Avleen Benitez','Suzanne Rios','Viaan Mcgowan','Ayrton Malone','Sanna Gonzales','Indiana Summers','Milli Guerra','Sade Boone','Zaine Webb','Nabila Correa','Anne-Marie Vazquez','Maariyah Bryan','Sumaya Legge','Susanna Hickman','Patrik Stephenson','Shannon Hogg','Ikrah Graham','Angelica Hoover','Daniyal Neal','Brooke Sadler','Gloria Mcleod','Randy Fry','Filip Wyatt','Leela Daniels','Bogdan Mcknight','Bilal Turnbull'];
	var name = names[Math.floor(Math.random() * names.length)];
	var details = [
		{
			"zip": 36112,
			"BAH": 1254,
			"rank": "Captain",
			"marital": "Married",
			"yearsOfService": 8,
			"tax": "Married Filing Jointly",
			"familySize": 2
		},
		{
			"zip": 99702,
			"BAH": 1464,
			"rank": "Airman First Class",
			"marital": "Married",
			"yearsOfService": 3,
			"tax": "Married Filing Jointly",
			"familySize": 4
		},
		{
			"zip": 99506,
			"BAH": 1566,
			"rank": "Staff Sergeant",
			"marital": "Single",
			"yearsOfService": 6,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 85707,
			"BAH": 1167,
			"rank": "2d Lt",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 85309,
			"BAH": 1320,
			"rank": "Airman Basic",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 72099,
			"BAH": 1518,
			"rank": "Tech Sergeant",
			"marital": "Married",
			"yearsOfService": 7,
			"tax": "Married Filing Jointly",
			"familySize": 2
		},
		{
			"zip": 95903,
			"BAH": 1689,
			"rank": "Senior Airman",
			"marital": "Single",
			"yearsOfService": 5,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 93523,
			"BAH": 1857,
			"rank": "Specialist 2",
			"marital": "Married",
			"yearsOfService": 4,
			"tax": "Married Filing Jointly",
			"familySize": 5
		},
		{
			"zip": 90009,
			"BAH": 3432,
			"rank": "Captain",
			"marital": "Single",
			"yearsOfService": 7,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 92508,
			"BAH": 2166,
			"rank": "1st Lt",
			"marital": "Married",
			"yearsOfService": 3,
			"tax": "Married Filing Jointly",
			"familySize": 2
		},
		{
			"zip": 94535,
			"BAH": 2664,
			"rank": "1st Lt",
			"marital": "Single",
			"yearsOfService": 3,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 93437,
			"BAH": 1671,
			"rank": "Airman 1st Class",
			"marital": "Single",
			"yearsOfService": 3,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 80011,
			"BAH": 2637,
			"rank": "Major",
			"marital": "Married",
			"yearsOfService": 13,
			"tax": "Married Filing Jointly",
			"familySize": 3
		},
		{
			"zip": 80914,
			"BAH": 1608,
			"rank": "Staff Sergeant",
			"marital": "Single",
			"yearsOfService": 12,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 19901,
			"BAH": 1248,
			"rank": "Specialist 3",
			"marital": "Single",
			"yearsOfService": 3,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 32542,
			"BAH": 1647,
			"rank": "Airman",
			"marital": "Married",
			"yearsOfService": 2,
			"tax": "Married Filing Jointly",
			"familySize": 2
		},
		{
			"zip": 32544,
			"BAH": 1662,
			"rank": "1st Lt",
			"marital": "Single",
			"yearsOfService": 2,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 33608,
			"BAH": 2124,
			"rank": "Captain",
			"marital": "Single",
			"yearsOfService": 6,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 32925,
			"BAH": 1755,
			"rank": "Specialist 3",
			"marital": "Married",
			"yearsOfService": 6,
			"tax": "Married Filing Jointly",
			"familySize": 2
		},
		{
			"zip": 31699,
			"BAH": 1080,
			"rank": "Sergeant",
			"marital": "Married",
			"yearsOfService": 6,
			"tax": "Married Filing Jointly",
			"familySize": 7
		},
		{
			"zip": 31098,
			"BAH": 1092,
			"rank": "Staff Sergeant",
			"marital": "Single",
			"yearsOfService": 7,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 96818,
			"BAH": 2118,
			"rank": "Specialist 1",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 96860,
			"BAH": 3777,
			"rank": "Major",
			"marital": "Married",
			"yearsOfService": 14,
			"tax": "Married Filing Jointly",
			"familySize": 2
		},
		{
			"zip": 83648,
			"BAH": 1443,
			"rank": "1st Lt",
			"marital": "Single",
			"yearsOfService": 3,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 62225,
			"BAH": 1098,
			"rank": "2d Lt",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 67037,
			"BAH": 801,
			"rank": "Airman 1st Class",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 71037,
			"BAH": 1806,
			"rank": "Tech Sergeant",
			"marital": "Married",
			"yearsOfService": 16,
			"tax": "Married Filing Jointly",
			"familySize": 4
		},
		{
			"zip": 20735,
			"BAH": 2061,
			"rank": "Specialist 4",
			"marital": "Single",
			"yearsOfService": 5,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 39705,
			"BAH": 741,
			"rank": "Senior Airman",
			"marital": "Single",
			"yearsOfService": 5,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 39534,
			"BAH": 1218,
			"rank": "Airman",
			"marital": "Married",
			"yearsOfService": 2,
			"tax": "Married Filing Jointly",
			"familySize": 3
		},
		{
			"zip": 65305,
			"BAH": 735,
			"rank": "Airman Basic",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 59402,
			"BAH": 756,
			"rank": "Specialist 4",
			"marital": "Single",
			"yearsOfService": 6,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 68005,
			"BAH": 1767,
			"rank": "Tech Sergeant",
			"marital": "Married",
			"yearsOfService": 6,
			"tax": "Married Filing Jointly",
			"familySize": 4
		},
		{
			"zip": 89169,
			"BAH": 1272,
			"rank": "Senior Airman",
			"marital": "Single",
			"yearsOfService": 3,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 88103,
			"BAH": 693,
			"rank": "Airman 1st Class",
			"marital": "Single",
			"yearsOfService": 3,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 88330,
			"BAH": 1443,
			"rank": "1st Lt",
			"marital": "Married",
			"yearsOfService": 3,
			"tax": "Married Filing Jointly",
			"familySize": 3
		},
		{
			"zip": 79563,
			"BAH": 1410,
			"rank": "Captain",
			"marital": "Single",
			"yearsOfService": 6,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 78236,
			"BAH": 1542,
			"rank": "2d Lt",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 84040,
			"BAH": 1572,
			"rank": "1st Lt",
			"marital": "Single",
			"yearsOfService": 3,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 99011,
			"BAH": 1110,
			"rank": "2d Lt",
			"marital": "Single",
			"yearsOfService": 1,
			"tax": "Single",
			"familySize": 1
		},
		{
			"zip": 82001,
			"BAH": 1038,
			"rank": "Senior Airman",
			"marital": "Married",
			"yearsOfService": 7,
			"tax": "Married Filing Jointly",
			"familySize": 7
		}
	]
	var detail = details[Math.floor(Math.random() * details.length)];

	var modifiers = [
		{
			description: "Oh no, your husband started selling Mary Kay!",
			change: "-$300 per month!"
		},
		{
			description: "You started Twitch streaming!",
			change: "+$250 per month!"
		},
		{
			description: "You're separated from your family!",
			change: "+$250 per month!"
		},
		{
			description: "Your wife started selling 'It Works!' wraps",
			change: "-$500 per month!"
		},
		{
			description: "You went to ERAU and have student loans!",
			change: "-$800 per month!"
		},
		{
			description: "You went to ERAU and have student loans!",
			change: "-$800 per month!"
		},
		{
			description: "Your husband started selling Pampered Chef!",
			change: "-$300 per month!"
		},
		{
			description: "Your wife bought a dSLR camera, and she's really good!",
			change: "+$450 per month!"
		},
		{
			description: "Your wife has student loans!",
			change: "-$450 per month!"
		},
		{
			description: "You had a child!",
			change: "-$550 per month!"
		},
		{
			description: "You started a freelance graphic design business!",
			change: "-$1500 per month!"
		},
		{
			description: "Your wife started selling LulaRoe leggings!",
			change: "-$800 per month!"
		},
		{
			description: "Your wife makes amazingly decorated cookies!",
			change: "+$850 per month!"
		},
		{
			description: "Your wife runs a daycare in your home!",
			change: "+$650 per month!"
		},
		{
			description: "Your husband fixes people's cars in the garage!",
			change: "+$550 per month!"
		},
		{
			description: "You programmed a Software as a Service platform!",
			change: "+$2500 per month!"
		},
		{
			description: "You started a pressure washing business!",
			change: "+$350 per month!"
		},
		{
			description: "You invested in real estate and rent out a property!",
			change: "+$250 per month!"
		},
		{
			description: "You fraternized with an enlisted member!",
			change: "Forfeit all pay and allowances, return to civilian sector"
		},
		{
			description: "You cut hair on the weekends!",
			change: "+$275 per month!"
		},
		{
			description: "You got addicted to a gacha video game!",
			change: "-$350 per month!"
		},
		{
			description: "You like to go out drinking every weekend!",
			change: "-$650 per month!"
		},
		{
			description: "Your husband bakes elaborate breads and sells them on base!",
			change: "+$175 per month!"
		},
		{
			description: "Your wife started selling Scentsy Candles!",
			change: "-$175 per month!"
		},
		{
			description: "You got a DUI!",
			change: "Subtract one rank, set marital status to 'Single' and recompute!"
		},
		{
			description: "You bought a ton of GME stock!",
			change: "-$3,000, then +$3,150, then -$50, then -$5,000"
		},
		{
			description: "Your husband started selling DoTerra!",
			change: "-$380 per month!"
		},
		{
			description: "Finance screwed up your pay, seemingly forever!",
			change: "-$680 per month!"
		},
		{
			description: "You cheated on your spouse on a deployment!",
			change: "-$1,750 per month in alimony and child support!"
		},
		{
			description: "You stole a USSF polo shirt from the BX!",
			change: "-$750 per month in suspended wages!"
		}
	]
	var modifier = modifiers[Math.floor(Math.random() * modifiers.length)];
</script>

<main>
	<div class="content">
	<h1><img src="{avatar}" alt="" height=150 width=150 style="vertical-align: middle; padding: 10px;">{detail.rank} {name}</h1>
		<table class="customTable">
			<tr>
				<th style="width:50%">Category</th>
				<th style="width:50%">Data</th>
			</tr>
			<tr>
				<td>Rank</td>
				<td>{detail.rank}</td>
			</tr>
			<tr>
				<td>Years of Service</td>
				<td>{detail.yearsOfService}</td>
			</tr>
			<tr>
				<td>Tax Filing Status</td>
				<td>{detail.tax}</td>
			</tr>
			<tr>
				<td>Family Size</td>
				<td>{detail.familySize}</td>
			</tr>
			<tr>
				<td>Living OCONUS</td>
				<td>No</td>
			</tr>
			<tr>
				<td>Zip Code</td>
				<td>{detail.zip}</td>
			</tr>
		</table>

		<div class="modifier">
			<h2>{modifier.description}</h2>
			<h3>{modifier.change}</h3>
		</div>

		<table class="customTable">
			<tr>
				<th style="width:50%">Category</th>
				<th style="width:50%">Cost</th>
			</tr>
			<tr>
				<td>Food</td>
				<td>${detail.familySize * 200}</td>
			</tr>
			<tr>
				<td>Cell Phone</td>
				<td>${cellPhone}</td>
			</tr>
			<tr>
				<td>Car Insurance</td>
				<td>${carInsurance}</td>
			</tr>
			<tr>
				<td>Car Payment</td>
				<td>${carPayment}</td>
			</tr>
			<tr>
				<td>Cable/Internet</td>
				<td>${cableInternet}</td>
			</tr>
			<tr>
				<td>Zip Code</td>
				<td>{detail.zip}</td>
			</tr>
		</table>


		<h2>Step 1</h2>
		<p><a href="https://militarypay.defense.gov/calculators/rmc-calculator/">Go to Military Compensation Calculator</a> and enter data.</p>
	
	<h2>Step 2</h2>
	<p>Go to <a href="https://docs.google.com/spreadsheets/d/18SpUa0JPiat1heE4jCwA_sCq5hZ9_T2rwA4su8vAZB0/template/preview">Google Sheets Budget</a></p>
</div>
</main>

<style>
	html {
		background: #eee;
		padding: 0;
		margin: 0;
	}

	main {
		text-align: left;
		padding: 1em;
		margin: 0 auto;
	}

	h1 {
		color: #1d13a1;
		text-transform: uppercase;
		font-size: 2em;
		font-weight: 500;
	}

	h2, h3 {
		color: #1d13a1
	}

	div.content {
		background: white;
		max-width: 800px;
		padding: 20px;
		margin: 25px auto;
		border-radius: 20px;
	}

	div.modifier {
		margin: 20px 50px;
		border: 1px solid #eee;
		border-radius: 15px;
		padding: 5px 25px;
		background: rgb(248, 242, 206);
		text-align: center;
	}

	table.customTable {
  width: 80%;
  background-color: #FFFFFF;
  border-collapse: collapse;
  border-width: 2px;
  border-color: #7ea8f8;
  border-style: solid;
	color: #000000;
	margin: 10px auto;
}

table.customTable td, table.customTable th {
  border-width: 2px;
  border-color: #7ea8f8;
  border-style: solid;
  padding: 5px;
}

table.customTable thead {
  background-color: #7ea8f8;
}

</style>