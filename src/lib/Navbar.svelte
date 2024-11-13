<script>
    let data = $props();
    import { page } from "$app/stores";
</script>


<div class = "flex w-full justify-between items-center p-1 px-3 border-b border-b-black border-dashed bg-white/80 backdrop-blur  static">
    <div class = "flex flex-col text-center text-[0.65rem]">
        <a href="/">
            <p class = "text-2xl font-extralight h-fit">Viswa B</p>
            <p class = "h-fit font-semibold">Graphic Designer</p>
        </a>
    </div>
    <ul class = "flex text-xs gap-2">
        <li class="{$page.url.pathname == '/About' ? "text-orange-500" : ""}"><a href="/About">About</a></li>
        <li class = "{$page.url.pathname == '/works' ? "text-orange-500" : ""}"><a href="/works">Works</a></li>
        <li><a href = "https://drive.google.com/file/d/1LLZqm127Rhr2CQaDJZsELabrkssS0yBu/view?usp=sharing">Resume</a></li>
        <!-- <li>Contact</li> -->
    </ul>
</div>