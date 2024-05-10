# Project Responsive Web Design using Bootstrap
## Date: 10/05/2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
### Index.html:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="assets/css/style.css">
</head>

<body>
    <div class="row">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="assets/css/images/AM.png" style="width: 100%;">
        </div>
        <div class="col-5" style="margin-top: 65px;">
            <a href="index.html">Home</a>
            <a href="people.html">People</a>
            <a href="product.html">Products</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="col-3" style="margin-top: 65px;">
            <i class="bi bi-facebook"></i>
            <i class="bi bi-twitter"></i>
            <i class="bi bi-instagram"></i>
        </div>
    </div>
    <div class="row2" style="margin-top: 20px;">
        <div class="col-1"></div>
        <div class="col-3" id="main">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/download (3).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Customized wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/download (4).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Kids wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (1).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Denim wears</p>
                </div>
            </div>
        </div>
        <div class="col-1"></div>
    </div>
    <div class="row3">
        <div class="col-1"></div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (2).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Casual wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (3).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Daily wears</p>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="card" style="width: 30rem;">
                <img src="assets/css/images/images (4).jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <p class="card-text" style="font-size: 30px; text-align: center;">Unisex wears</p>
                </div>
            </div>
        </div>
        <div class="col-1"></div>
    </div>
</body>

</html>
```

### Style.css:
```
body{
    background-color: rgb(232, 227, 227);
}
a,i{
    text-decoration: none;
    font-size: 20px;
    color: black;
    padding: 50px;

}
.row2,.row3,.name,.people
{
    display: flex;
    margin: 30px;

}
.card-img-top {
    width: 100%;
    height: 600px; 
}

.card {
    max-width: 30rem;
    margin-left: 20px;
}
.contact
{
    margin: 100px;
    font-size: 25px;
}
.name
{
    margin: 100px;
    align-items: center;
}
```

## OUTPUT:
![image](https://github.com/Aishwarya-TM/Web-Ex-10/assets/127846109/137ac505-be9a-4621-aab9-a91777b3a47d)

![image](https://github.com/Aishwarya-TM/Web-Ex-10/assets/127846109/d44062a9-084e-4b07-ba60-c6666b6c8d61)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
