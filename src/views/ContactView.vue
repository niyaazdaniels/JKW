<template>
    <div class="container-fluid">

        <div class="row">
            <div class="col-12">
                <h4 class="display-4 text-center">Contact US</h4>
                <hr class="my-4">
            </div>

            <div class="col-xs-12 col-md-6 " id="contact">

                <form class="mb-sm-4" id="for">

                    <div class="form-group">
                        <label for="exampleFormControlInput2">Name</label>
                        <input type="name" class="form-control" id="exampleFormControlInput2" placeholder="Name">
                    </div>


                    <div class="form-group">
                        <label for="exampleFormControlInput1">Cellphone</label>
                        <input type="tel" class="form-control" id="exampleFormControlInput1"
                            placeholder="+27 1234 678">
                    </div>

                    <div class="form-group">
                        <label for="exampleFormControlTextarea1">Message</label>
                        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" placeholder="I'd like to make a booking"></textarea>
                    </div>

                    <button type="submit" class="btn btn-info m-2">Submit</button>
                </form>

            </div>

            <div class="card border-0 m-2"  id="contact">
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3305.7913100712476!2d18.49248297657611!3d-34.04922397315807!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc43dc259af437%3A0xbd9230b26b24a568!2s6%20Reddy%20Ave%2C%20Grassy%20Park%2C%20Cape%20Town%2C%207888!5e0!3m2!1sen!2sza!4v1768762490891!5m2!1sen!2sza"
                    width="fit-content" height="450" style="border:0;" allowfullscreen="" loading="lazy"
                    referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>


        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
body {
    text-align: center;
}


p {
    color: #8f8f8f;
}

/* Headings */

.big-heading {
    font-size: 3.5rem;
    line-height: 1.5;
}

.section-heading {
    font-size: 3rem;
    line-height: 1.5;
}

/* Containers */

.container-fluid {
    padding: 7% 15%;
}

/* Sections */

.colored-section {
    background-color: #ff4c68;
    color: #fff;
}

.white-section {
    background-color: #fff;
}

/* Navigation Bar */

.navbar {
    padding: 0 0 4.5rem;
}

.navbar-brand {
    font-size: 2.5rem;
    font-weight: bold;
}

.nav-item {
    padding: 0 18px;
}

.nav-link {
    font-size: 1.2rem;
}

/* Buttons */

.download-button {
    margin: 5% 3% 5% 0;
}

/* Title Section */

#title {
    background-color: #ff4c68;
    color: #fff;
    text-align: left;
}

#title .container-fluid {
    padding: 3% 15% 7%;
}

/* Title Image */

.title-image {
    width: 60%;
    transform: rotate(25deg);
    position: absolute;
    right: 30%;
}

/* Features Section */

#features {
    position: relative;
}

.feature-title {
    font-size: 1.5rem;
}

.feature-box {
    padding: 4.5%;
}

.icon {
    color: #ef8172;
    margin-bottom: 1rem;
}

.icon:hover {
    color: #ff4c68;
}

/* Testimonial Section */

#testimonials {
    background-color: #ef8172;
}

.testimonial-text {
    font-size: 3rem;
    line-height: 1.5;
}

.testimonial-image {
    width: 10%;
    border-radius: 100%;
    margin: 20px;
}


#press {
    background-color: #ef8172;
    padding-bottom: 3%;
}

.press-logo {
    width: 15%;
    margin: 20px 20px 50px;
}

/* Pricing Section */

#pricing {
    padding: 100px;
}

.price-text {
    font-size: 3rem;
    line-height: 1.5;
}

.pricing-column {
    padding: 3% 2%;
}

/* CTA Section */


/* Footer Section */


.social-icon {
    margin: 20px 10px;
}

@media (max-width: 1028px) {

    #title {
        text-align: center;
    }

    .title-image {
        position: static;
        transform: rotate(0);
    }
}
</style>