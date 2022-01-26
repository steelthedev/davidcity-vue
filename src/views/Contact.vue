<template>
     <section class="contact">
            <div class="container">
                <div class="row justify-content-center mt-5 pt-5">
                    <div class="col-md-12 col-lg-8 text-center">
                        <h2>
                         Send Us A Message
                        </h2>
    
                    </div>
            </div>
            <div class="row justify-content-center mt-5">
                <div class="col-md-4 col-lg-4 text-center" data-aos="fade-right" data-aos-delay="200">
                    <div class="c-icon">
                        <i class="fa fa-phone "></i>
                        <h3 class="mt-3">Call us</h3>
                        <span>+234 654 873 42</span>
                    </div>
                </div>

                <div class="col-md-4 col-lg-4 text-center" data-aos="fade-up" data-aos-delay="250">
                    <div class="c-icon">
                        <i class="fa fa-map "></i>
                        <h3 class="mt-3">Visit us</h3>
                        <span>Ogbede Villa , Iyin-Ekiti</span>
                    </div>
                </div>

                <div class="col-md-4 col-lg-4 text-center" data-aos="fade-left" data-aos-delay="200">
                    <div class="c-icon">
                        <i class="fa fa-fax "></i>
                        <h3 class="mt-3">Mail us</h3>
                        <span>ajakanika@mailing.com</span>
                    </div>
                </div>

              
            </div>

            <form action="" class="mt-5" method="POST">
                <div class="row justify-content-center">
                    <div class="col-md-6 col-md-6">
                        <div class="form-group">
                            <label for="name">
                                Name
                            </label>
                            <input type="text" class="form-control shadow-none" name="f_name" required maxlength="200">
                        </div>
                        </div>


                        <div class="col-md-6 col-lg-6">
                            <div class="form-group">
                                <label for="name">
                                    Email
                                </label>
                                <input type="email" class="form-control shadow-none" name="email" required maxlength="200">
                            </div>
                        </div>


                        <div class="col-md-12 col-lg-12">
                            <div class="form-group">
                                <label for="Message">
                                    Message
                                </label>
                                <textarea  rows="10" class="form-control shadow-none" name="message" required maxlength></textarea>
                            </div>


                            <button class="btn btn-outline-white c-btn shadow-none" type="submit">Send Message</button>
                        </div>
                </div>
            </form>




            </div>
        </section>

</template>

<script>

</script>