# wp_tags
後から整理するよ

タクソノミーに属していて（アーカイブ）んでシングルにも
<?php if(is_tax('articlecat','telework') || has_term( 'telework', 'articlecat' )): ?>



?php get_template_part( '_modules_meta' ); ?>



<?php wp_deregister_script('jquery'); ?>


tax
    <?php get_header();
        $template_uri = get_template_directory_uri();
        if(have_posts()) {
            $type = get_post_type_object($post->post_type);
            $term_object = get_queried_object();
        }
    ?>


<?php if(is_home()){ echo ' home'; }?>
