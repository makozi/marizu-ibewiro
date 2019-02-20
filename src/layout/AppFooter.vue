<template>
    <footer class="footer has-cards">
        <div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/landing" title="Landing Page">
                            <img v-lazy="'img/theme/landing.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/profile" title="Profile Page">
                            <img v-lazy="'img/theme/profile.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 class="text-primary font-weight-light mb-2">Thank you for supporting us!</h3>
                    <h4 class="mb-0 font-weight-light">Let's get in touch on any of these platforms.</h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">
                
                    <a target="_blank" rel="noopener" href=""
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-twitter"></i>
                    </a>
                    <a target="_blank" rel="noopener" href=""
                       class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Like us">
                        <i class="fa fa-facebook-square"></i>
                    </a>
                    <a target="_blank" rel="noopener" href=""
                       class="btn btn-neutral btn-icon-only btn-google btn-lg btn-round" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-google"></i>
                    </a>
                    <a target="_blank" rel="noopener" href=""
                       class="btn btn-neutral btn-icon-only btn-linkedin btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Connect on LinkedIn">
                        <i class="fa fa-linkedin"></i>
                    </a>
                    
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a href="" target="_blank" rel="noopener">Marizu-Ibewiro</a>.
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        
                        
                        <li class="nav-item">
                            <router-link to="/blog" class="nav-link">
                        <span class="btn-inner--icon">
                         <i class="fa fa-envelop mr-2"></i>
                        </span>
                        <span class="nav-link-inner--text">Blog</span>
                    </router-link>
                        </li>
                        <li class="nav-item">
                            <a href="http://makozi.netlify.com" class="nav-link" target="_blank" rel="noopener">Made with <i class="fa fa-heart red" style="color:red;"></i> Makozi</a>
                        </li>
                        
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
