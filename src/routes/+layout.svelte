<script>
	import '../app.postcss';
</script>
<nav class="p-2 bg-slate-500 text-white">
    <a href="/">NuestroServer</a>
    <a href="/getting-started">Intro rápida</a>
</nav>
<div class="container">
    <slot></slot>
</div>

<style>
    .container{
        max-width: 70ch;
        margin: 0 auto;
    }
</style>