    <!-- start footer -->

        <footer id="footer" class="footer-wrap"> 
            <div class="container">
                <?php if( is_active_sidebar('bottom') ){ ?>
                    <div class="bottom">
                        <div class="row">
                            <div class="col-sm-12 text-center footer-wrapper">
                                <?php if (is_active_sidebar('bottom')) {?>
                                    <div class="bottom-widget text-center">
                                        <?php dynamic_sidebar('bottom'); ?>
                                    </div>
                                <?php } ?>
                            </div>
                        </div>
                    </div>
                <?php } ?>
                <?php if ( get_theme_mod( 'copyright_en', true ) || get_theme_mod( 'footer_share', true ) ) { ?>
                    <div class="footer-copyright">
                        <div class="row">    
                            <?php if( get_theme_mod( 'footer_share', true ) ) { ?>
                                <div class="col-md-6">
                                    <?php get_template_part('lib/social-link')?>
                                </div> <!-- end row -->
                            <?php } ?>
                            <?php if( get_theme_mod( 'copyright_en', true ) ) { ?>
                                <div class="col-md-6 text-right copy-wrapper">
                                    <?php echo wp_kses_post(balanceTags( get_theme_mod( 'copyright_text', '© 2016 Your Company.  Designed By <a href="http://themeum.com/" target="_blank"> THEMEUM</a>') )); ?>
                                </div> <!-- end row -->
                            <?php } ?>
                        </div> <!-- end row -->
                    </div> <!-- end row -->
                <?php } ?>
            </div> <!-- end container -->
        </footer>
    </div> <!-- #page -->
<?php wp_footer(); ?>
</body>
</html>
