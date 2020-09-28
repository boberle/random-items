# Detailed list of files and fields

Jump to:

- <a href="#familyname">familyname</a>
- <a href="#givenname">givenname</a>
- <a href="#person">person</a>
- <a href="#company">company</a>
- <a href="#product">product</a>
- <a href="#city">city</a>
- <a href="#country">country</a>
- <a href="#currency">currency</a>
- <a href="#lake">lake</a>
- <a href="#building">building</a>
- <a href="#address">address</a>
- <a href="#unique_email">unique_email</a>
- <a href="#hobby">hobby</a>
- <a href="#occupation">occupation</a>
- <a href="#language">language</a>
- <a href="#western_language">western_language</a>
- <a href="#car">car</a>
- <a href="#battle">battle</a>
- <a href="#fable">fable</a>


## File `family_names.csv`<a class="bookmark-header" name="familyname"></a>


Number of rows: 1405.

**Field `name`:**

- number of unique values: 1349
- example of values: <code>Nikolaidis, Gaultier, Marchand</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 16

**Field `language`:**

- description of the field: the language the name belongs to ("Dupont" is French, "Simpson" English)
- number of unique values: 8
- example of values: <code>de, cz, ru</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 2

**Field `frequency`:**

- description of the field: how many people with that name have a Wikipedia entry (by country)
- number of unique values: 132
- example of values: <code>159, 84, 23</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 2 to 579

## File `given_names.csv`<a class="bookmark-header" name="givenname"></a>


Number of rows: 2530.

**Field `name`:**

- number of unique values: 2054
- example of values: <code>Alison, Christel, Mattie</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 15

**Field `gender`:**

- description of the field: Mary is female, John male
- number of unique values: 2
- example of values: <code>f, m</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 1 to 1

**Field `language`:**

- description of the field: the language the name belongs to ("Jean" is French, "John" English)
- number of unique values: 8
- example of values: <code>gr, ru, en</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 2

**Field `frequency`:**

- description of the field: how many people with that name have a Wikipedia entry (by country)
- number of unique values: 311
- example of values: <code>144, 263, 214</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 1 to 2597

## File `persons.csv`<a class="bookmark-header" name="person"></a>


Number of rows: 1500.

**Field `wiki_id`:**

- number of unique values: 1500
- example of values: <code>&lt;Richard_Wilson_(scholar)&gt;, &lt;Dahlia_Lithwick&gt;, &lt;Verónica_Segura&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 8 to 51

**Field `familyname`:**

- number of unique values: 1420
- example of values: <code>Kuni, Pavlenko, Pashkus</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 19

**Field `givenname`:**

- number of unique values: 1047
- example of values: <code>Zahid, Randi, Jan</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 18

**Field `gender`:**

- number of unique values: 2
- example of values: <code>m, f</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 1 to 1

**Field `email`:**

- number of unique values: 1500
- example of values: <code>rick-loomis@skynet.be, penha@uol.com.br, r-henrick@me.com</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 11 to 36

**Field `occupation`:**

- number of unique values: 269
- example of values: <code>songwriter, actor, film producer</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 24

**Field `birth_date`:**

- number of unique values: 1469
- example of values: <code>2001-04-19, 1934-12-08, 1961-01-07</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 10 to 10

**Field `birth_country`:**

- number of unique values: 108
- example of values: <code>Romania, Algeria, Cuba</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 20

**Field `birth_continent`:**

- number of unique values: 7
- example of values: <code>Oceania, Central America, South America</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 15

**Field `company`:**

- number of unique values: 944
- example of values: <code>China Three Gorges Corporation, Nokia, National Oilwell Varco</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 58

**Field `street`:**

- number of unique values: 1478
- example of values: <code>26 avenue de Saint-Ouen, 275 5th Street, 131 rue Saint-Lazare</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 49

**Field `city`:**

- number of unique values: 527
- example of values: <code>La Rochelle, Lancaster, Pearland</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 24

**Field `zip`:**

- number of unique values: 647
- example of values: <code>85721-0045, 18837, 67154</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 10

**Field `region`:**

- number of unique values: 53
- example of values: <code>North Dakota, Occitanie, Provence-Alpes-Côte d&#x27;Azur</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 26

**Field `region_abbr`:**

- number of unique values: 39
- example of values: <code>WI, AL, MA</code>
- number of null values: 372
- type (pandas): `object`
- string length range: 2 to 2

**Field `country`:**

- number of unique values: 2
- example of values: <code>United States, France</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 13

**Field `continent`:**

- number of unique values: 2
- example of values: <code>North America, Europe</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 13

**Field `phone_code`:**

- number of unique values: 2
- example of values: <code>1, 33</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 1 to 33

**Field `phone`:**

- number of unique values: 1500
- example of values: <code>1548785154, 1367243542, 179358611</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 111632377 to 9998887915

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 1406
- example of values: <code>Carolyn Brent, also known as Carolyn A. Brent, is ..., Russell Impagliazzo is a professor of computer sci..., Montserrat Carulla i Ventura (born 1930) is a Cata...</code>
- number of null values: 94
- type (pandas): `object`
- string length range: 30 to 4938

**Field `picture`:**

- number of unique values: 1365
- example of values: <code>Lillian Stewart Carl publicity photo.jpg, Joan Bassie Jennifer Bassey 1967.JPG, Abduweli.profile.png</code>
- number of null values: 121
- type (pandas): `object`
- string length range: 7 to 214

**Field `picture_url`:**

- number of unique values: 1361
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/6/6..., https://upload.wikimedia.org/wikipedia/commons/b/b..., https://upload.wikimedia.org/wikipedia/commons/7/7...</code>
- number of null values: 121
- type (pandas): `object`
- string length range: 58 to 226

**Field `picture_thumb`:**

- number of unique values: 1361
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/en/thumb/1/...</code>
- number of null values: 121
- type (pandas): `object`
- string length range: 58 to 413

**Field `picture_url_local`:**

- number of unique values: 1379
- example of values: <code>00920.jpg, 00019.jpg, 00935.jpg</code>
- number of null values: 121
- type (pandas): `object`
- string length range: 9 to 10

**Field `picture_thumb_local`:**

- number of unique values: 1379
- example of values: <code>00428.jpg, 00960.jpg, 00348.jpg</code>
- number of null values: 121
- type (pandas): `object`
- string length range: 9 to 10

## File `companies.csv`<a class="bookmark-header" name="company"></a>


Number of rows: 1555.

**Field `wiki_id`:**

- number of unique values: 1555
- example of values: <code>&lt;Hyundai_Motor_Company&gt;, &lt;MTS_(network_provider)&gt;, &lt;Hanergy&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 60

**Field `name`:**

- number of unique values: 1553
- example of values: <code>News Corporation, Bank of the Philippine Islands, Iberdrola</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 58

**Field `industry`:**

- number of unique values: 437
- example of values: <code>industrial automation, health care, market expansion services</code>
- number of null values: 3
- type (pandas): `object`
- string length range: 2 to 78

**Field `people`:**

- description of the field: number of people
- number of unique values: 952
- example of values: <code>13762, 22800, 14295</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 10000 to 927839

**Field `country`:**

- number of unique values: 77
- example of values: <code>Kuwait, Belgium, United States</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 26

**Field `continent`:**

- number of unique values: 7
- example of values: <code>Europe, Africa, Asia</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 15

**Field `web`:**

- description of the field: web site
- number of unique values: 1406
- example of values: <code>http://www.clarion.com/, http://www.thalesgroup.com/, http://www.ceskedrahy.cz/en/default.htm</code>
- number of null values: 146
- type (pandas): `object`
- string length range: 13 to 77

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 1399
- example of values: <code>News Corporation or News Corp may refer to:

News ..., Allergan, Inc. was an American global pharmaceutic..., AU Optronics (AUO; Chinese: 友達光電) is a company in ...</code>
- number of null values: 156
- type (pandas): `object`
- string length range: 52 to 3473

**Field `logo`:**

- number of unique values: 406
- example of values: <code>RockTenn logo.jpg, BSH Bosch und Siemens Hausgeräte logo.svg, Thai life logo.png</code>
- number of null values: 1149
- type (pandas): `object`
- string length range: 5 to 76

**Field `logo_url`:**

- number of unique values: 315
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/9/9..., https://upload.wikimedia.org/wikipedia/en/2/28/Con..., https://upload.wikimedia.org/wikipedia/commons/3/3...</code>
- number of null values: 1240
- type (pandas): `object`
- string length range: 55 to 114

**Field `logo_thumb`:**

- number of unique values: 315
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/en/thumb/6/..., https://upload.wikimedia.org/wikipedia/en/thumb/4/...</code>
- number of null values: 1240
- type (pandas): `object`
- string length range: 61 to 193

**Field `logo_url_local`:**

- number of unique values: 315
- example of values: <code>00026.jpg, 00070.svg, 00056.svg</code>
- number of null values: 1240
- type (pandas): `object`
- string length range: 9 to 10

**Field `logo_thumb_local`:**

- number of unique values: 315
- example of values: <code>00123.png, 00246.png, 00079.png</code>
- number of null values: 1240
- type (pandas): `object`
- string length range: 9 to 10

## File `products.csv`<a class="bookmark-header" name="product"></a>


Number of rows: 1296.

**Field `wiki_id`:**

- number of unique values: 1296
- example of values: <code>&lt;Escape_from_Davao&gt;, &lt;Baiga_vasara&gt;, &lt;Palayathu_Amman&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 77

**Field `type`:**

- description of the field: movie, video game, album or book
- number of unique values: 4
- example of values: <code>video game, book, movie</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 10

**Field `title`:**

- number of unique values: 1296
- example of values: <code>Mouse Trap Hotel, Highwire Act Live in St. Louis 2003, The Hacker Crackdown</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 1 to 75

**Field `author`:**

- number of unique values: 1252
- example of values: <code>Ishai Setton, Cédric Klapisch, David Salsburg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 98

**Field `date`:**

- number of unique values: 47
- example of values: <code>1982, 2000, 2001</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 1794 to 2017

**Field `language`:**

- number of unique values: 50
- example of values: <code>Korean, Portuguese, Mandarin</code>
- number of null values: 644
- type (pandas): `object`
- string length range: 4 to 12

**Field `country`:**

- number of unique values: 59
- example of values: <code>England, Turkey, Netherlands</code>
- number of null values: 693
- type (pandas): `object`
- string length range: 2 to 14

**Field `continent`:**

- number of unique values: 7
- example of values: <code>North America, South America, Oceania</code>
- number of null values: 693
- type (pandas): `object`
- string length range: 4 to 15

**Field `remark`:**

- number of unique values: 911
- example of values: <code>Greenwillow Books/Harper Collins Publishers, UK: William Heinemann Ltd., US: Pocket Books, Tim Matheson, Cynthia Nixon, Joe Chrest, Joel Murr...</code>
- number of null values: 137
- type (pandas): `object`
- string length range: 3 to 308

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 1208
- example of values: <code>Animal is the debut studio album by American singe..., Paris Connections is a 2010 British film directed ..., The Cowboy Way is a 1994 American action comedy fi...</code>
- number of null values: 88
- type (pandas): `object`
- string length range: 37 to 3198

**Field `picture`:**

- description of the field: the cover
- number of unique values: 899
- example of values: <code>TiranaYearZero.jpg, Ratchet and Clank cover.jpg, The Fault in Our Stars.jpg</code>
- number of null values: 397
- type (pandas): `object`
- string length range: 7 to 111

**Field `picture_url`:**

- number of unique values: 854
- example of values: <code>https://upload.wikimedia.org/wikipedia/en/2/2c/My_..., https://upload.wikimedia.org/wikipedia/en/4/4e/2pm..., https://upload.wikimedia.org/wikipedia/en/d/d8/The...</code>
- number of null values: 442
- type (pandas): `object`
- string length range: 55 to 165

**Field `picture_thumb`:**

- number of unique values: 854
- example of values: <code>https://upload.wikimedia.org/wikipedia/en/thumb/0/..., https://upload.wikimedia.org/wikipedia/en/thumb/d/..., https://upload.wikimedia.org/wikipedia/en/b/ba/PSP...</code>
- number of null values: 442
- type (pandas): `object`
- string length range: 56 to 291

**Field `picture_url_local`:**

- number of unique values: 854
- example of values: <code>00191.jpg, 00101.jpg, 00157.jpg</code>
- number of null values: 442
- type (pandas): `object`
- string length range: 9 to 10

**Field `picture_thumb_local`:**

- number of unique values: 854
- example of values: <code>00125.jpg, 00723.jpg, 00384.jpg</code>
- number of null values: 442
- type (pandas): `object`
- string length range: 9 to 10

## File `cities.csv`<a class="bookmark-header" name="city"></a>


Number of rows: 808.

**Field `wiki_id`:**

- number of unique values: 808
- example of values: <code>&lt;Scottsdale,_Arizona&gt;, &lt;Vadodara&gt;, &lt;Shenzhen&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 51

**Field `name`:**

- number of unique values: 795
- example of values: <code>Chestermere, La Ceiba, Bordeaux</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 37

**Field `zipcode`:**

- number of unique values: 410
- example of values: <code>21000, 30001, 070XX</code>
- number of null values: 341
- type (pandas): `object`
- string length range: 3 to 7

**Field `region`:**

- number of unique values: 485
- example of values: <code>Vila Baleira, Gelderland, Southern Norway</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 39

**Field `country`:**

- number of unique values: 164
- example of values: <code>Tanzania, Equatorial Guinea, Ethiopia</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 32

**Field `continent`:**

- number of unique values: 7
- example of values: <code>Africa, Oceania, South America</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 15

**Field `latitude`:**

- number of unique values: 738
- example of values: <code>33.45, 42.266666666666666, 40.86</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -41.288888888888884 to 69.68277777777779

**Field `longitude`:**

- number of unique values: 753
- example of values: <code>4.433333333333334, -1.78, 29.23333333333333</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -171.75 to 178.4419

**Field `people`:**

- description of the field: number of people
- number of unique values: 781
- example of values: <code>143486, 518981, 126414</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 10870 to 18679763

**Field `area`:**

- number of unique values: 531
- example of values: <code>297.36, 304.34, 153.9</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: 0.0 to 8000036.0

**Field `web`:**

- description of the field: web site
- number of unique values: 532
- example of values: <code>http://www.minsk.gov.by, http://www.savannahga.gov/, http://www.kandywhc.org/</code>
- number of null values: 273
- type (pandas): `object`
- string length range: 16 to 99

**Field `mayor`:**

- number of unique values: 85
- example of values: <code>Alain Juppé, Dagur Bergþóruson Eggertsson, Jean-Luc Moudenc</code>
- number of null values: 723
- type (pandas): `object`
- string length range: 8 to 28

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 800
- example of values: <code>Sheffield is a city and metropolitan borough in So..., Monrovia  is the capital city of the West African ..., Casablanca (Arabic: الدار البيضاء‎, romanized: ad-...</code>
- number of null values: 8
- type (pandas): `object`
- string length range: 97 to 5922

## File `countries.csv`<a class="bookmark-header" name="country"></a>


Number of rows: 180.

**Field `wiki_id`:**

- number of unique values: 180
- example of values: <code>&lt;San_Marino&gt;, &lt;Israel&gt;, &lt;Montserrat&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 34

**Field `name`:**

- number of unique values: 180
- example of values: <code>Uzbekistan, Oman, Japan</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 32

**Field `continent`:**

- number of unique values: 7
- example of values: <code>Central America, Oceania, Africa</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 15

**Field `capital`:**

- number of unique values: 179
- example of values: <code>Warsaw, Kuala Lumpur, Kampala</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 19

**Field `latitude`:**

- number of unique values: 142
- example of values: <code>51.0, 2.5, -1.9402777777777769</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -42.0 to 72.0

**Field `longitude`:**

- number of unique values: 151
- example of values: <code>65.0, -84.0, 8.0</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -175.0 to 179.0

**Field `currency`:**

- number of unique values: 138
- example of values: <code>New Zealand dollar, Peruvian sol, Brunei dollar</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 7 to 29

**Field `people`:**

- description of the field: number of people
- number of unique values: 180
- example of values: <code>102374044, 37873253, 5426252</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 1612 to 1376049000

**Field `area`:**

- number of unique values: 179
- example of values: <code>316.0, 18274.0, 88361.0</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: 0.0 to 17075200.0

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 178
- example of values: <code>Israel (; Hebrew: יִשְׂרָאֵל‎; Arabic: إِسْرَائِيل..., Syria (Arabic: سوريا‎, romanized: Sūriyā), officia..., Chile ( (listen), ; Spanish: [ˈtʃile]), officially...</code>
- number of null values: 2
- type (pandas): `object`
- string length range: 630 to 6250

**Field `picture`:**

- description of the field: the flag
- number of unique values: 180
- example of values: <code>Flag of Mali.svg, Flag of Malta.svg, Flag of Cuba.svg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 16 to 48

**Field `picture_url`:**

- number of unique values: 180
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/3/3..., https://upload.wikimedia.org/wikipedia/commons/0/0..., https://upload.wikimedia.org/wikipedia/commons/5/5...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 64 to 100

**Field `picture_thumb`:**

- number of unique values: 180
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 98 to 165

**Field `picture_url_local`:**

- number of unique values: 180
- example of values: <code>00099.svg, 00085.svg, 00147.svg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 9

**Field `picture_thumb_local`:**

- number of unique values: 180
- example of values: <code>00106.png, 00150.png, 00148.png</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 9

**Field `imagemap`:**

- description of the field: a location map
- number of unique values: 180
- example of values: <code>Grenada in its region.svg, Location Brunei ASEAN.svg, Location Benin AU Africa.svg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 12 to 80

**Field `imagemap_url`:**

- number of unique values: 179
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/3/3..., https://upload.wikimedia.org/wikipedia/commons/e/e..., https://upload.wikimedia.org/wikipedia/commons/c/c...</code>
- number of null values: 1
- type (pandas): `object`
- string length range: 64 to 172

**Field `imagemap_thumb`:**

- number of unique values: 179
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu...</code>
- number of null values: 1
- type (pandas): `object`
- string length range: 93 to 309

**Field `imagemap_url_local`:**

- number of unique values: 179
- example of values: <code>00004.png, 00010.svg, 00140.svg</code>
- number of null values: 1
- type (pandas): `object`
- string length range: 9 to 9

**Field `imagemap_thumb_local`:**

- number of unique values: 179
- example of values: <code>00095.png, 00163.png, 00048.png</code>
- number of null values: 1
- type (pandas): `object`
- string length range: 9 to 9

## File `currencies.csv`<a class="bookmark-header" name="currency"></a>


Number of rows: 7.

**Field `name`:**

- number of unique values: 7
- example of values: <code>Canadian dollar, Australian dollar, US dollar</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 17

**Field `code`:**

- number of unique values: 7
- example of values: <code>CAD, JPY, AUD</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 3

## File `lakes.csv`<a class="bookmark-header" name="lake"></a>


Number of rows: 1085.

**Field `wiki_id`:**

- number of unique values: 1085
- example of values: <code>&lt;Henrys_Lake&gt;, &lt;Pihlajavesi_(Saimaa)&gt;, &lt;Lake_Abijatta&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 44

**Field `name`:**

- number of unique values: 1067
- example of values: <code>Yamdrok Lake, Lake Pedder, Gezhouba Dam</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 37

**Field `country`:**

- number of unique values: 118
- example of values: <code>Romania, Croatia, Uganda</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 32

**Field `continent`:**

- number of unique values: 7
- example of values: <code>Central America, Asia, Europe</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 15

**Field `latitude`:**

- number of unique values: 1056
- example of values: <code>38.20166666666667, 47.11666666666667, 57.01388888888889</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -51.23333333333333 to 74.54277777777777

**Field `longitude`:**

- number of unique values: 1073
- example of values: <code>149.06972222222225, 26.655555555555555, 51.213</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -156.8 to 177.08333333333337

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 1049
- example of values: <code>Bhimtal Lake is a lake in the town of Bhimtal, in ..., The Prespa lakes are two freshwater lakes, with th..., The Petit-Saut Dam is a gravity dam on the Sinnama...</code>
- number of null values: 36
- type (pandas): `object`
- string length range: 33 to 5327

**Field `caption`:**

- number of unique values: 1049
- example of values: <code>Satellite image of Lake Beyşehir, Lake Couchiching is the small teardrop-shaped lake..., from the northeast shore at sunset</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 296

**Field `picture`:**

- number of unique values: 1077
- example of values: <code>Thingvallavatn.jpg, Lake Glenbawn at late sunset, April 2013.jpg, Maardu jarv.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 8 to 96

**Field `picture_url`:**

- number of unique values: 1076
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/3/3..., https://upload.wikimedia.org/wikipedia/commons/f/f..., https://upload.wikimedia.org/wikipedia/commons/c/c...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 60 to 233

**Field `picture_thumb`:**

- number of unique values: 1076
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 81 to 427

**Field `picture_url_local`:**

- number of unique values: 1085
- example of values: <code>00822.jpg, 00616.jpg, 00832.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 10

**Field `picture_thumb_local`:**

- number of unique values: 1085
- example of values: <code>00641.jpg, 00519.jpg, 00114.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 10

## File `buildings.csv`<a class="bookmark-header" name="building"></a>


Number of rows: 427.

**Field `wiki_id`:**

- number of unique values: 427
- example of values: <code>&lt;Sanctuary_of_Madonna_of_Miracles&gt;, &lt;Domus_Sanctae_Marthae&gt;, &lt;Ferrara_Cathedral&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 67

**Field `name`:**

- number of unique values: 421
- example of values: <code>Church of San Lorenzo, Teatro Español, Basilica di Santa Maria Maggiore</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 7 to 52

**Field `country`:**

- number of unique values: 26
- example of values: <code>Australia, Syria, Bulgaria</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 26

**Field `continent`:**

- number of unique values: 5
- example of values: <code>Oceania, Europe, Africa</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 13

**Field `latitude`:**

- number of unique values: 425
- example of values: <code>37.9828, 45.64638888888889, 40.2536</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -37.816853 to 63.9687

**Field `longitude`:**

- number of unique values: 425
- example of values: <code>24.27673333333333, -80.8531, 14.504833333333336</code>
- number of null values: 0
- type (pandas): `float64`
- numeric range: -118.3 to 144.967384

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 367
- example of values: <code>The New Cathedral (Spanish: Catedral Nueva) is, to..., The Assumption of the Virgin Cathedral (Spanish: C..., San Miniato al Monte (St. Minias on the Mountain) ...</code>
- number of null values: 60
- type (pandas): `object`
- string length range: 70 to 5257

**Field `caption`:**

- number of unique values: 363
- example of values: <code>Carrer Marlet, in the old Jewish quarter of Barcel..., The Palace of the Doges view from &quot;Piazza Matteott..., The façade of Santa Maria Novella, completed by Le...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 224

**Field `picture`:**

- number of unique values: 427
- example of values: <code>Burgos - Las Huelgas 10.jpg, Chiesa dei Gesuiti (Facciata).jpg, St Mary Magdalene&#x27;s Church (Greek Orthodox), St Le...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 10 to 200

**Field `picture_url`:**

- number of unique values: 427
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/9/9..., https://upload.wikimedia.org/wikipedia/commons/4/4..., https://upload.wikimedia.org/wikipedia/commons/b/b...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 62 to 266

**Field `picture_thumb`:**

- number of unique values: 427
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 85 to 329

**Field `picture_url_local`:**

- number of unique values: 427
- example of values: <code>00093.jpg, 00310.jpg, 00213.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 10

**Field `picture_thumb_local`:**

- number of unique values: 427
- example of values: <code>00294.jpg, 00309.jpg, 00257.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 10

## File `addresses.csv`<a class="bookmark-header" name="address"></a>


Number of rows: 1277.

**Field `street`:**

- number of unique values: 1273
- example of values: <code>1918 Thomas Jefferson Parkway, 3338 East Main Street, 89 rue de Verdun</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 48

**Field `city`:**

- number of unique values: 693
- example of values: <code>Tonopah, Épinay-sur-Seine, Sedona</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 24

**Field `zipcode`:**

- number of unique values: 854
- example of values: <code>22560, 32807, 85388</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 10

**Field `region`:**

- description of the field: region/state
- number of unique values: 60
- example of values: <code>Pennsylvania, Minnesota, West Virginia</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 26

**Field `abbr`:**

- description of the field: region/state abbrevation
- number of unique values: 43
- example of values: <code>WI, FL, MO</code>
- number of null values: 523
- type (pandas): `object`
- string length range: 2 to 2

**Field `country`:**

- number of unique values: 2
- example of values: <code>United States, France</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 13

**Field `continent`:**

- number of unique values: 2
- example of values: <code>North America, Europe</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 13

**Field `complete`:**

- description of the field: complete address on one line
- number of unique values: 1273
- example of values: <code>22 cours Tourny, 24000 Périgueux, 11005 S.W. 84th Street, Kendall FL 33173, 2119 Rapids Drive, Racine WI 53404</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 24 to 72

## File `unique_emails.csv`<a class="bookmark-header" name="unique_email"></a>


Number of rows: 5000.

**Field `email`:**

- number of unique values: 5000
- example of values: <code>timuhlig82@laposte.net, nunata@gmail.com, f.xing@yahoo.fr</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 39

**Field `givenname`:**

- number of unique values: 1647
- example of values: <code>Hanns, Winfried, Nelly</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 15

**Field `familyname`:**

- number of unique values: 1202
- example of values: <code>Uhlig, Kuznetsov, Favre</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 16

**Field `language`:**

- description of the field: the language the name belongs to ("Jean" is French, "John" English)
- number of unique values: 8
- example of values: <code>ru, en, fr</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 2

**Field `gender`:**

- description of the field: Mary is female, John male
- number of unique values: 2
- example of values: <code>f, m</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 1 to 1

## File `hobbies.csv`<a class="bookmark-header" name="hobby"></a>


Number of rows: 242.

**Field `hobby`:**

- number of unique values: 237
- example of values: <code>Amateur journalism, Roque, Cycle polo</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 35

**Field `type`:**

- description of the field: sport...
- number of unique values: 2
- example of values: <code>sport, hobby</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 5

## File `occupations.csv`<a class="bookmark-header" name="occupation"></a>


Number of rows: 269.

**Field `occupation`:**

- number of unique values: 269
- example of values: <code>lyricist, composer, literary critic</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 24

## File `languages.csv`<a class="bookmark-header" name="language"></a>


Number of rows: 248.

**Field `language`:**

- number of unique values: 248
- example of values: <code>Faroese, Bosnian, Ripuarian</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 19

**Field `iso`:**

- number of unique values: 176
- example of values: <code>ud, eu, ss</code>
- number of null values: 19
- type (pandas): `object`
- string length range: 2 to 2

**Field `iso3`:**

- number of unique values: 227
- example of values: <code>nau, sqi, kaa</code>
- number of null values: 19
- type (pandas): `object`
- string length range: 2 to 3

**Field `speakers`:**

- description of the field: number of speakers
- number of unique values: 217
- example of values: <code>1080000, 30000000, 38000000</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 1000 to 568000000

## File `western_languages.csv`<a class="bookmark-header" name="western_language"></a>


Number of rows: 27.

**Field `language`:**

- number of unique values: 27
- example of values: <code>Slovene, Croatian, Icelandic</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 10

**Field `iso`:**

- number of unique values: 27
- example of values: <code>uk, ru, fr</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 2 to 2

## File `cars.csv`<a class="bookmark-header" name="car"></a>


Number of rows: 556.

**Field `wiki_id`:**

- number of unique values: 556
- example of values: <code>&lt;Opel_Insignia&gt;, &lt;Lada_Riva&gt;, &lt;MG_ZS_SUV&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 40

**Field `model`:**

- number of unique values: 556
- example of values: <code>Fisker Karma, Toyota Previa, Oullim Spirra</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 4 to 38

**Field `class`:**

- number of unique values: 157
- example of values: <code>Sports car (S), Full-size crossover SUV, Sports car, Roadster</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 61

**Field `date`:**

- number of unique values: 53
- example of values: <code>1984, 1966, 1988</code>
- number of null values: 0
- type (pandas): `int64`
- numeric range: 1931 to 2017

**Field `manufacturer`:**

- number of unique values: 135
- example of values: <code>Chrysler LLC, Daewoo, Oullim Motors Inc.</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 3 to 19

**Field `length`:**

- number of unique values: 442
- example of values: <code>206.5 in, 5000 mm, 4634 mm</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 6 to 9

**Field `height`:**

- number of unique values: 340
- example of values: <code>1940 mm, 76.6 in, 1745 mm</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 8

**Field `width`:**

- number of unique values: 298
- example of values: <code>1579 mm, 1840 mm, 79.9 in</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 8

**Field `description`:**

- description of the field: summary of the Wikipedia page
- number of unique values: 532
- example of values: <code>Tesla Roadster may refer to:

Tesla Roadster (2008..., The Acura ILX is a compact executive car produced ..., The Mazda 6 or Mazda6 (known as the Mazda Atenza i...</code>
- number of null values: 24
- type (pandas): `object`
- string length range: 73 to 2642

**Field `picture`:**

- number of unique values: 556
- example of values: <code>2000 Tata Indica.JPG, Daewoo Nubira Sedan front.jpg, Cadillac CT6 04 2015.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 107

**Field `picture_url`:**

- number of unique values: 556
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/3/3..., https://upload.wikimedia.org/wikipedia/commons/9/9..., https://upload.wikimedia.org/wikipedia/commons/2/2...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 61 to 312

**Field `picture_thumb`:**

- number of unique values: 556
- example of values: <code>https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu..., https://upload.wikimedia.org/wikipedia/commons/thu...</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 83 to 585

**Field `picture_url_local`:**

- number of unique values: 556
- example of values: <code>00225.jpg, 00172.jpg, 00400.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 9

**Field `picture_thumb_local`:**

- number of unique values: 556
- example of values: <code>00456.jpg, 00053.jpg, 00446.jpg</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 9 to 9

## File `battles.csv`<a class="bookmark-header" name="battle"></a>


Number of rows: 227.

**Field `wiki_id`:**

- number of unique values: 227
- example of values: <code>&lt;Battle_of_Andros_(246_BC)&gt;, &lt;Battle_of_Gabiene&gt;, &lt;Battle_of_Embata&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 7 to 40

**Field `name`:**

- number of unique values: 202
- example of values: <code>Battle of Idomene, First Persian invasion of Greece, Battle of Tanagra</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 38

**Field `conflict`:**

- number of unique values: 181
- example of values: <code>Battle of Selinus, Battle of Notium, Battle of Pharos</code>
- number of null values: 22
- type (pandas): `object`
- string length range: 12 to 32

**Field `date`:**

- number of unique values: 181
- example of values: <code>Some time between 540 BC and 535 BC, 490 BC, 277 BC</code>
- number of null values: 20
- type (pandas): `object`
- string length range: 5 to 39

**Field `outcome`:**

- number of unique values: 105
- example of values: <code>Gallic victory, Macedonia restores control of the Balkans, Decisive Macedonian-Achaean victory</code>
- number of null values: 30
- type (pandas): `object`
- string length range: 8 to 140

**Field `abstract`:**

- number of unique values: 215
- example of values: <code>The Siege of Tauromenium was laid down by Dionysiu..., The Battle of Amphipolis (Greek: Μάχη της Αμφίπολη..., The Battle of the Himera River was fought in 446 B...</code>
- number of null values: 12
- type (pandas): `object`
- string length range: 93 to 4071

**Field `abstract_html`:**

- number of unique values: 215
- example of values: <code>&lt;p&gt;The &lt;b&gt;Battle of Andros&lt;/b&gt; was an obscure nava..., &lt;p&gt;The &lt;b&gt;Battle of the Crimissus&lt;/b&gt; (also spelle..., &lt;p&gt;The &lt;b&gt;Battle of Selinus&lt;/b&gt;, which took place ...</code>
- number of null values: 12
- type (pandas): `object`
- string length range: 119 to 4163

**Field `content`:**

- description of the field: the whole wikipedia article
- number of unique values: 215
- example of values: <code>The Indian campaign of Alexander the Great began i..., The Battle of Orneae was an engagement that took p..., The Siege of Halicarnassus was fought between Alex...</code>
- number of null values: 12
- type (pandas): `object`
- string length range: 93 to 59466

**Field `content_html`:**

- description of the field: the whole wikipedia article
- number of unique values: 215
- example of values: <code>&lt;p&gt;The &lt;b&gt;Siege of Tauromenium&lt;/b&gt; was laid down b..., &lt;p&gt;The &lt;b&gt;Battle of Plataea&lt;/b&gt; was the final land..., &lt;p&gt;The &lt;b&gt;Battle of Pydna&lt;/b&gt; was fought in 148 BC...</code>
- number of null values: 12
- type (pandas): `object`
- string length range: 134 to 84950

## File `fables.csv`<a class="bookmark-header" name="fable"></a>


Number of rows: 41.

**Field `wiki_id`:**

- number of unique values: 36
- example of values: <code>&lt;The_Lion_in_Love_(fable)&gt;, &lt;Belling_the_cat&gt;, &lt;The_Goose_That_Laid_the_Golden_Eggs&gt;</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 7 to 81

**Field `title`:**

- number of unique values: 36
- example of values: <code>Belling the cat, Momus, The Sick Kite</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 79

**Field `author`:**

- number of unique values: 3
- example of values: <code>Laurientius Abstemius, Aesop, La Fontaine</code>
- number of null values: 0
- type (pandas): `object`
- string length range: 5 to 21

**Field `abstract`:**

- number of unique values: 30
- example of values: <code>The Frogs Who Desired a King is one of Aesop&#x27;s Fab..., The Deer without a Heart is an ancient fable, attr..., Hares are proverbially timid and a number of fable...</code>
- number of null values: 6
- type (pandas): `object`
- string length range: 78 to 2371

**Field `abstract_html`:**

- number of unique values: 30
- example of values: <code>&lt;p&gt;In Greek mythology, the figure of &lt;b&gt;Horkos&lt;/b&gt;..., &lt;p&gt;&lt;b&gt;The Sick Kite&lt;/b&gt; is one of Aesop&#x27;s Fables a..., &lt;p&gt;The situation of the &lt;b&gt;Eagle Wounded by an Arr...</code>
- number of null values: 6
- type (pandas): `object`
- string length range: 92 to 2485

**Field `content`:**

- description of the field: the whole wikipedia article
- number of unique values: 30
- example of values: <code>The Deer without a Heart is an ancient fable, attr..., The lion grown old is counted among Aesop’s Fables..., The Mountain in Labour is one of Aesop&#x27;s Fables an...</code>
- number of null values: 6
- type (pandas): `object`
- string length range: 886 to 25929

**Field `content_html`:**

- description of the field: the whole wikipedia article
- number of unique values: 30
- example of values: <code>&lt;p&gt;&lt;b&gt;The mouse turned into a maid&lt;/b&gt; is an ancie..., &lt;p&gt;A &lt;b&gt;wolf in sheep&#x27;s clothing&lt;/b&gt; is an idiom o..., &lt;p&gt;The fable of &lt;b&gt;The Walnut Tree&lt;/b&gt; is one of A...</code>
- number of null values: 6
- type (pandas): `object`
- string length range: 931 to 28551


