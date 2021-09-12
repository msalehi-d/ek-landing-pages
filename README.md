# ek-landing-pages

page template:
```
<?php get_header(); ?>
<div class="container">
    <div class="text-right py-3 small text-secondary breadcrumb-single">
        <a href="<?php echo home_url(); ?>">اعتبارکالا</a>
        / <?php the_title() ?>
    </div>
</div>

<div class="page mb-5">
    <div class="container">
        <div class="bg-white p-4 border shadow-sm text-right rtl rounded">
            <div class="row">
                Template
                <?php the_content(); ?>
            </div>
        </div>
    </div>
</div>

<?php get_footer(); ?>
```
