<script>
	//Names
	var names = ['Zi Hurley','Javan Avalos','Marcus Johnson','Rianne Mill','Penny Valenzuela','Kayne Emery','Leilani Read','Mercedes Ochoa','Freyja Oconnor','Trinity Redfern','Mikaela O\'Gallagher','Kenneth Downs','Miriam Begum','Hawwa Mellor','Joy Zuniga','Abdur-Rahman Mccallum','Kairo Kidd','Renae Casey','Klay Merrill','Sian Rudd','Nolan Wolfe','Edie Walters','Isobel Black','Jokubas Goldsmith','Keenan Busby','Linda Trejo','Ismael Turner','Tj Mcnamara','Bob Nichols','Maaria Rayner','Iain Forbes','Jon-Paul Horn','Etta Patton','Kirstin Howell','Alessandra Maddox','Marisa Sharples','Nadia Ellison','John Chung','Ammarah Bray','Corrina Gill','Joanne Howard','Samira Zavala','Kezia Rivera','Bernard Odom','Yolanda Cash','Lennie Pollard','Lily Pham','Nicolas Henry','Kobi English','Charley Howells','Rio Schmitt','Joseff Nieves','Arielle Ray','Cecelia Sheppard','Paris Carty','Karan Rivas','Eshan Gaines','Austin Storey','Kimberly Wiggins','Lydia Davila','Aarush Markham','Tamera Knights','Amber-Rose Avery','Kie Gibbs','Donnell Hilton','Aliya Wormald','Sahil Armstrong','Rafferty Garrison','Simone Williamson','Vincenzo Mathews','Bethany Pratt','Merlin Perez','Tasmin Ferrell','Indigo Petty','Avleen Benitez','Suzanne Rios','Viaan Mcgowan','Ayrton Malone','Sanna Gonzales','Indiana Summers','Milli Guerra','Sade Boone','Zaine Webb','Nabila Correa','Anne-Marie Vazquez','Maariyah Bryan','Sumaya Legge','Susanna Hickman','Patrik Stephenson','Shannon Hogg','Ikrah Graham','Angelica Hoover','Daniyal Neal','Brooke Sadler','Gloria Mcleod','Randy Fry','Filip Wyatt','Leela Daniels','Bogdan Mcknight','Bilal Turnbull'];
	var name = names[Math.floor(Math.random() * names.length)];
	//Ranks
	var ranks = ['2d Lieutenant','1st Lieutenant','Captain']
	var rank = ranks[Math.floor(Math.random() * ranks.length)];
	//Zip code
	var zips = [36112,99702,99506,85707,85309,72099,95903,93523,90009,92508,94535,93437,80011,80914,19901,32542,32544,33608,32925,31699,31098,96818,96860,83648,62225,67037,71037,20735,39705,39534,65305,59402,68005,89169,88103,88330,79563,78236,84040,99011,82001]
	var zip = zips[Math.floor(Math.random() * zips.length)];
	//Zip code
	var details = [
		{
			"zip": 36112,
			"BAH": "$1,254",
			"rank": "Captain",
			"marital": "Married"
		},
		{
			"zip": 99702,
			"BAH": "$1,464",
			"rank": "Airman First Class",
			"marital": "Married"
		}
	]
	var detail = details[Math.floor(Math.random() * details.length)];
	//Married
	var maritalStatuses = ['Married','Single']
	var maritalStatus = maritalStatuses[Math.floor(Math.random() * maritalStatuses.length)];
</script>

<main>
	<h1>{rank} {name}</h1>
	<h2>Step 1</h2>
	<p><a href="https://militarypay.defense.gov/calculators/rmc-calculator/">Go to Military Compensation Calculator</a></p>
	<p>Years of Service: <br />2nd Lt - 1<br />1st Lt - 3<br />Captain - 6</p>
	<p>Marital Status: <b>{maritalStatus}</b></p>
	<p>Family Size: <b>1</b> if single, <b>2</b> if married</p>
	<p>Not OCONUS</p>
	<p>Zip Code: <b>{detail.zip}</b></p>
	<p>BAH: {detail.BAH}</p>

	<h2>Step 2</h2>
	<p>Go to <a href="https://docs.google.com/spreadsheets/d/18SpUa0JPiat1heE4jCwA_sCq5hZ9_T2rwA4su8vAZB0/template/preview">Google Sheets Budget</a></p>

</main>

<style>
	main {
		text-align: left;
		padding: 1em;
		max-width: 500px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 2em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>