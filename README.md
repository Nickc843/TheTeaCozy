# TheTeaCozy

--HTML--

<!DOCTYPE HTML>
<html>
    <link href="theteacozycss.css" rel="stylesheet">
    <header>
        <div class="picture">
            <img class="image" src="https://content.codecademy.com/courses/freelance-1/unit-4/img-tea-cozy-logo.png?_gl=1*1x1s8e8*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2MzcyNzM3Ni4zMTUuMS4xNjYzNzI3Mzg0LjUyLjAuMA..">
        </div>
        <div class="nav">
            <ul>
                <li>Mission</li>
                <li>Featured Tea</li>
                <li>Locations</li>
            </ul>
        </div>
    </header>
    <body>
        <section class="our-mission">
            <div class="mission-wrap">
                <h2 class="the-mission">Our Mission</h2>
                <h4 class="mission-statement">Handpicked, Artisanally Curated, Free Range, Sustainable, Small Batch, Fair Trade, Organic Tea</h4>
            </div>
        </section>
        <section class="tea-of-the-month">
            <h2>Tea of the Month</h2>
            <h4>What's Steeping at The Tea Cozy?</h4>
        </section>
        <section class="menu">
            <div class="flavors">
                <figure class="menu-picture">
                    <img src="https://content.codecademy.com/courses/freelance-1/unit-4/img-berryblitz.jpg?_gl=1*1ad4emk*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2Mzg5NjQ4MC4zMTYuMS4xNjYzODk2NDg1LjU1LjAuMA..">
                    <figcaption>Fall Berry Blitz Tea</figcaption>
                </figure>
                <figure class="menu-picture">
                    <img src="https://content.codecademy.com/courses/freelance-1/unit-4/img-spiced-rum.jpg?_gl=1*1ad4emk*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2Mzg5NjQ4MC4zMTYuMS4xNjYzODk2NDg1LjU1LjAuMA..">
                    <figcaption>Spiced Rum Tea</figcaption>
                </figure>
                <figure class="menu-picture">
                    <img src="https://content.codecademy.com/courses/freelance-1/unit-4/img-donut.jpg?_gl=1*1l4aau3*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2Mzg5NjQ4MC4zMTYuMS4xNjYzODk2NDg1LjU1LjAuMA..">
                    <figcaption>Seasonal Donut</figcaption>
                </figure>
                <figure class="menu-picture">
                    <img src="https://content.codecademy.com/courses/freelance-1/unit-4/img-myrtle-ave.jpg?_gl=1*vsg1b6*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2Mzg5NjQ4MC4zMTYuMS4xNjYzODk2NDg1LjU1LjAuMA..">
                    <figcaption>Myrtle Ave Tea</figcaption>
                </figure>
                <figure class="menu-picture">
                    <img src="https://content.codecademy.com/courses/freelance-1/unit-4/img-bedford-bizarre.jpg?_gl=1*vsg1b6*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2Mzg5NjQ4MC4zMTYuMS4xNjYzODk2NDg1LjU1LjAuMA..">
                    <figcaption>Bedford Bizarre Tea</figcaption>
                </figure>
            </div>
        </section>
        <section class="locations">
            <h2 class="location-title">Locations</h2>
            <div class="all-locations">
                <section class="location-block">
                    <h3>Downtown</h3>
                    <p>384 West 4th St</p>
                    <p>Suite 108</p>
                    <p>Portland, Maine</p>
                </section>
                <section class="location-block">
                    <h3>East Bayside</h3>
                    <p>3433 Phisherman's Avenue</p>
                    <p>(Northwest Corner)</p>
                    <p>Portland, Maine</p>
                </section>
                <section class="location-block">
                    <h3>Oakdale</h3>
                    <p>515 Crescent Avenue</p>
                    <p>Second Floor</p>
                    <p>Portland, Maine</p>
                </section>
            </div>
        </section>
    </body>
    <footer>
        <section>
            <section class="footer">
                <h2>The Tea Cozy</h2>
                <h5 class="contact">contact@theteacozy.com</h5>
                <h5 class="number">917-555-8904</h5>
            </section> 
        </section>
        <h5 class="copyright">copyright The Tea Cozy 2017</h5>
    </footer>
</html>



--CSS--


html {
    background-color: black;
    color: seashell;
    font-family: Helvetica;
    opacity: 0.9;
    font-size: 22px;
    padding-top: 69px;
    text-align: center;
    display: flex;
    justify-content: center;
}

/*Nav bar*/

header {
    overflow: hidden;
    display: flex;
    flex-direction: row;
    position: fixed !important;
    left: 0 !important;
    top: 0 !important;
    width: 100%;
    border-bottom: 1px solid seashell;
    align-items: center;
    height: 69px;
    justify-content: space-between;
    opacity: 1 !important;
    background-color: black;
}

.picture {
    display: flex;
    justify-content: flex-start;
}

.image {
    height: 50px;
    width: auto;
    margin-left: 10px;
    align-items: center;
}

.nav {
    list-style: none;
    align-items: center;
    justify-content: flex-end;
}

li {
    display: inline;
    text-decoration: underline;
    justify-content: space-between;
}    

/*Mission Statement*/

.our-mission {
    background-image: url("https://content.codecademy.com/courses/freelance-1/unit-4/img-mission-background.jpg?_gl=1*1qafz5n*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2Mzg5NjQ4MC4zMTYuMS4xNjYzODk2NDg1LjU1LjAuMA..");
    display: flex;
    justify-content: center;
    align-items: center;
    height: 700px;
    width: 1200px;
    flex-wrap: wrap;
}

.mission-wrap {
    background-color: black;
    width: 1200px;
}

/*Tea of the Month*/

.tea-of-the-month {
    margin-top: 100px
}

.menu {
    margin-top: 10px;
    width: 1000px;
    display: inline-flex;
}

.flavors {
    display: flex;
    flex-wrap: wrap;
    align-content: stretch;
}

.menu-picture {
    align-self: center;
    margin: auto;
    margin-top: 20px;
}

.menu-picture img{
    height: 200px;
    width: 300px;
    padding-bottom: 10px;    
}

/*Locations*/

.locations {
    background-image: url('https://content.codecademy.com/courses/freelance-1/unit-4/img-locations-background.jpg?_gl=1*uquhk1*_ga*MTk1MTUyODMyNi4xNjM5OTQxMjA5*_ga_3LRZM6TM9L*MTY2Mzg5NjQ4MC4zMTYuMS4xNjYzODk2NDg1LjU1LjAuMA..');
    margin-top: 100px;
    height: 500px;
    width: 1200px;
    display: flex;
    flex-wrap: wrap;
    align-content: center;
    justify-content: center;
}

.location-title {
    display: inline-flex;
    align-self: top;
    justify-self: center;
    margin: 0;
    padding: 0;
}

.all-locations {
    display: flex;
    justify-content: center;
    align-self: center;
}

.location-block {
    background-color: black;
    margin: 15px 40px auto 40px;
    opacity: 1;
    width: 300px;
}

.location-block p {
    margin-top: 50px; 
}

/*Footer*/

.footer {
    height: 200px;
}

.contact {
    margin-top: 50px;
}

h5.copyright {
    overflow: hidden;
    display: flex;
    flex-direction: row;
    position: absolute !important;
    left: 0 !important;
    width: 100%;
    justify-content: space-between;
}




