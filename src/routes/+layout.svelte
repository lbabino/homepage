<script>
	import '../app.postcss';
</script>
<nav class="p-2 bg-slate-500 text-white items-center">
    <a class="ml-2 hover:shadow-sm hover:shadow-black transition-shadow hover:duration-75" href="/">NuestroServer</a>
    <div class="p-2 bg-amber-200 rounded-xl flex flex-row items-center shadow-sm shadow-black">
        <div>
            <p class="text-blue-950 text-[0.85em]"><i>¡Sitio en contrucción!</i></p>
            <p class="text-blue-950 text-[0.65em]"><i>Disculpe las molestias</i></p>
        </div>
        <p class="text-2xl ">👷‍♂️</p>
    </div>
    <a class="mr-2 hover:shadow-sm hover:shadow-black transition-shadow hover:duration-75" href="/getting-started">Intro rápida</a>
</nav>
<div class="container max-w-prose">
    <slot></slot>
</div>

<style>
</style>

