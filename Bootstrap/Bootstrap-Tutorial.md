
## Bootstrap Tutorial

## 1. Container Class
##
![image](https://github.com/Krishna-Gopal-Pathak/Web-Development/assets/142927819/b2d614aa-f423-4b69-8edc-db69295ff0e5)
##
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/6824cd84-1006-4429-9e57-425512a52dac)
##


## 2. Row and Column

![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/2d7d3e7f-d312-49f6-8e1c-8f0a10c2b4ea)


## 3. Break Point
```bash
<div class="w-100"></div>
```
Screenshots

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
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/73c8d81e-ddbf-491b-8c3d-b193f2e0d977)
##

## 4. Row Column Class
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/5964277d-6c56-434c-b200-b3175c825eb9)
##

After Second Column || Break Column Equally
```bash
row-cols-2
```

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
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/6569cee2-b22d-4f17-bec1-a1d03374547a)
##




## 5. Col Class
```bash
In col class we do not mention number in the end
```
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/54775e8f-5630-4bd7-90e1-1e7c7ed2e7a0)
##

## 6. Grid System
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/9e6a0405-65cd-4066-8746-538f38db7846)
##

## 7. Grid Col Class

```bash
In grid col class we mention number in the end
```
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/1e1facf7-131a-4f64-b5b8-3b77c33ecac6)
##

## 8. Offset
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/faea5a19-586d-47c0-9744-735754050b30)
##
##
![image](https://github.com/Krishna-Gopal-Pathak/Software-Development/assets/142927819/e1b00318-1465-4465-8edb-824dfb4aa781)
##
