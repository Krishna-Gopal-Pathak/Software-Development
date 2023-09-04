
## Bootstrap Tutorial

## 1. Container Class


```bash
.container
.container-fluid
```
##
![image](https://github.com/Krishna-Gopal-Pathak/Web-Development/assets/142927819/b2d614aa-f423-4b69-8edc-db69295ff0e5)
##
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/6824cd84-1006-4429-9e57-425512a52dac)
##


## 2. Row and Column

```bash
<div class=".container">
	<div class="row">
		<div class="col">
			<p>Hello</p>	
		</div>

		<div class="col">
			<p>Hello 1</p>
		</div>

		<div class="col">
			<p>Hello 2</p>
		</div>
	</div>
</div>
```
Screenshot

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/2d7d3e7f-d312-49f6-8e1c-8f0a10c2b4ea)


## Break Point
```bash
<div class="w-100"></div>
```


```bash
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Bootstrap</title>
	<link rel="stylesheet" href="./bootstrap.css">
	<style>
		.container{
			border:5px solid black;
		}

      .row{
	      border:3px solid blue;
      }

    .col{
	      border:1px solid red;
    }
	</style>
</head>
<body>
	<div class="container">
		<p>Container</p>
		<div class="row">
			<p>Row</p>
			<div class="col">
				<p>Column-1</p>
			</div>
			<div class="col">
				<p>Column-2</p>
			</div>
			<div class="w-100"></div>  Break Point
			<div class="col">
				<p>Column-3</p>
			</div>
			<div class="col">
				<p>Column-4</p>
			</div>
			<div class="col">
				<p>Column-5</p>
			</div>
			<div class="col">
				<p>Column-6</p>
			</div>
		</div>
		
	</div>

</body>
</html>
```

Screenshots

##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/73c8d81e-ddbf-491b-8c3d-b193f2e0d977)
##

## Row Column Class
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/5964277d-6c56-434c-b200-b3175c825eb9)
##

After Second Column || Break Column Equally
```bash
row-cols-2
```

```bash
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Bootstrap</title>
	<link rel="stylesheet" href="./bootstrap.css">
	<link rel="stylesheet" href="./style.css">
	<style>
		.container{
			border:5px solid black;
		}

      .row{
	      border:3px solid blue;
      }

.col{
	border:1px solid red;
}
	</style>
</head>
<body>
	<div class="container">
		<p>Container</p>
		<div class="row row-cols-2">  
			<div class="col">
				<p>Column-1</p>
			</div>
			<div class="col">
				<p>Column-2</p>
			</div>
			<div class="col">
				<p>Column-3</p>
			</div>
			<div class="col">
				<p>Column-4</p>
			</div>
			<div class="col">
				<p>Column-5</p>
			</div>
			<div class="col">
				<p>Column-6</p>
			</div>
		</div>
		
	</div>

</body>
</html>
```
Screenshot

##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/6569cee2-b22d-4f17-bec1-a1d03374547a)
##




## Col Class for Responsive
```bash
In col class we do not mention number.
```
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/54775e8f-5630-4bd7-90e1-1e7c7ed2e7a0)
##

## 3. Grid System
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/9e6a0405-65cd-4066-8746-538f38db7846)
##

## Grid Col Class for responsive

```bash
In grid col class we mention number in the end
```
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/1e1facf7-131a-4f64-b5b8-3b77c33ecac6)
##

## 8. Offset

```bash
offset-3  //Value will be 1-12
```
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/faea5a19-586d-47c0-9744-735754050b30)
##
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/e1b00318-1465-4465-8edb-824dfb4aa781)
##


## Reordering
```bash
order-last       
order-first
```

##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/53c531e2-a111-41a8-8102-3730177cf9c7) 
##

## Reordering for responsive
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/f348eb13-071d-427f-8205-9909278d396f)
##

## Reordering With Grid Numbers
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/f3cb55b6-5d38-427d-83a7-7682a54fc85a)
##

##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/ed6c6031-5270-4708-a1a5-4d37325871af)
##

## Nesting

##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/bff1f48a-b3f7-4e1f-9c54-d7841bc8e674)
##


Screenshot

```bash
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Bootstrap</title>
	<link rel="stylesheet" href="./bootstrap.css">
	<link rel="stylesheet" href="./style.css">
	<style>
		.container{
			border:5px solid black;

		}

		.row{
			border:3px solid blue;
		}

		.col{
			border:1px solid red;
		}

		.col-md-6{
			background: red;
		}


	</style>
</head>
<body>
	<div class="container">
		<div class="row">
			<div class="col-md-6">
				<h2>Heading goes here</h2>
				<div class="row">
					<div class="col-md-6">
						<h3>Heading 1</h3>
						<p>Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem Loremv </p>
					</div>

					<div class="col-md-6 green">
						<h2>Heading 2</h2>
						<p>Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem LoremLorem Lorem Lorem Lorem Lorem Loremv </p>

						<div class="row ">
							<div class="col-md-12">
								<h2>Heading 3</h2>
								<p>Lorem Lorem Lorem Lorem Lorem Lorem Lorem Lorem LoremLorem Lorem Lorem Lorem Lorem Loremv </p>
							</div>

						</div>
					</div>

				</div>
			</div>
		</div>
	</div>

</body>
</html>
```

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/aa697e98-3329-455f-9c45-bce0b31a1f60)


## Margin Class

```bash
m-auto
ml-auto
mr-auto
```
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/9892e548-24f8-49e3-81e4-e1939f91bada)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/360f8dde-a5d4-431d-9c91-9349c2decfc2)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/95a0c26a-a005-4c39-b804-b5af584c1bb2)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/8c1f6d60-7299-45bf-a336-a9ae1db54e09)



## List Group

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/30e71c0c-58c8-40c3-a465-f299dcc7a78f)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/b00a2332-1dcc-41b3-a712-fca3b4c4431e)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/637a9344-67d6-4d95-b3f7-de568ce3145f)


![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/1173c447-5b26-405e-ab65-926014b185b2)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/76644ab8-6bf4-4aa6-87bb-fb6fcdf37640)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/3045f779-361a-4e08-8fa7-ca55a706be41)


## Table Classes

```bash
table-hover
```

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/792cb1bf-1fcf-4c6d-9822-f3e88456ab07)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/d1e30dca-d4d2-4488-8da9-77f8161176e4)


![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/1e7f6010-1e41-4b3c-99e3-b5c31e041021)


![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/94f07751-f17a-4be7-81bc-2c614a849220)


![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/6ce8f8d9-dbf5-468b-b27e-95f89a2d46ff)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/e6eb69dc-6a00-4e0d-984a-d151eef496f4)


![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/46cc3b28-a115-4d8b-ab33-7c2b474eea8e)


![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/b736ef06-c99c-44c5-ae89-a6c3f55d2382)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/93fe643f-24c8-4777-b0ea-852fe00e1afd)

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/26a2ad9d-f091-4381-ab4b-3ae85e3d238e)






