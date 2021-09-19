# ek-landing-pages

page template with header and footer:
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
# Template page without Header and footer

```
<!doctype html>
<html lang="fa" dir="rtl">
<head>

    <meta http-equiv="Content-Type" content="text/html; charset=<?php bloginfo('charset') ?>"/>
    <meta name="viewport" content="width=device-width,initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta name="mobile-web-app-capable" content="yes">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
    <?php wp_head(); ?>
    <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-PYPRDYXYKY"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-PYPRDYXYKY');
</script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha512-SfTiTlX6kk+qitfevl/7LibUOeJWlt9rbyDn92a1DqWOw9vWG2MFoays0sgObmWazO5BQPiFucnnEAjpAB+/Sw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
	
</head>
<body>
<!-- Start content -->



<!-- end content -->
 <?php wp_footer() ?>
```
