# project1
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>module2-solution</title>
</head>
<link rel="stylesheet" type="text/css" href="css/style.css">

<body>
    <h1>Our Menu</h1>
    <section class="column-lg-4 colmn-md-6 colmn-sm-12">
        <div>
            <p class="sub1">Chicken</p>
            <p class="content">
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
            </p>
        </div>
    </section>
    <section class="column-lg-4 colmn-md-6 colmn-sm-12">
        <div>
            <p class="sub2">Beef</p>
            <p class="content">
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
        </div>
    </section>
    <section class="column-lg-4 colmn-md-12 colmn-sm-12">
        <div>
            <p class="sub3">Sushi</p>
            <p class="content">
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.
            </p>
        </div>
</body>

</html>



/*basic style*/
    * {
        box-sizing: border-box;
    }

    body {
        background-color: white;
    }

    h1 {
       margin-bottom: 15px;
    text-align: center;
    color: #ff4532;
    font-size: 50px;
    }

    section {
        position: relative;
        padding: 15px;
        width: 90%;
    }

    p {
        position: relative;
        clear: right;
    }

    div {
        position: relative;
        background-color: gray;
        border: 3.5px solid black;
        width: 100%;
        margin-left: auto;
        margin-right: auto;
        margin-bottom: auto;
    }

    .sub1 {
        float: right;
        width: 100px;
        padding: 5px;
        margin: -3px -3px 0px;
        border: 3.5px solid black;
        text-align: center;
        font-size: 125%;
        font-weight: bold;
        background-color: #FFB6C1;

    }

    .sub2 {
        float: right;
        color: white;
        width: 100px;
        padding: 5px;
        margin: -3px -3px 0px;
        border: 3.5px solid black;
        text-align: center;
        font-size: 125%;
        font-weight: bold;
        background-color: #FF0000;

    }

    .sub3 {
        color: black;
        float: right;
        width: 100px;
        padding: 5px;
         margin: -3px -3px 0px;
        border: 3.5px solid black;
        text-align: center;
        font-size: 125%;
        font-weight: bold;
        background-color: rgb(223, 212, 121);

    }

    .content {
        padding: 5px;
        border: none;
        background-color: gray;
        font-family: Helvetica;
        color: black;
        margin: 3px ;
        height: 150px;
        overflow: auto;
    }

    .row {
        width: 90%;
    }

    /*desktop version*/
    @media (min-width: 992px) {
        .column-lg-4 {
            float: left;
            width: 33.33%;
        }
    }

    /*tablet version*/
    @media (min-width: 768px) and (max-width: 991px) {
        .colmn-md-6 {
            float: left;
            width: 50%;
            margin-left: auto;
            margin-right: auto;
        }

        .colmn-md-12 {
            float: left;
            width: 100%;
            margin-left: auto;
            margin-right: auto;
        }
    }

    /*mobile version*/
    @media (max-width: 767px) {
        .colmn-sm-12 {
            float: left;
            width: 100%;
        }
    }
