<!-- <script>
    let images = [];
    const loadImages = async () =>{
        const response = await fetch('/personal');
        const data = await response.json();
        images = data;
    };

    loadImages();
</script>
<div class = "text-xs p-4 font-semibold">
    My Personal Works
    {#each images as image}
    <img src={image} alt = "personal"/>
    {/each}
</div> -->
<script>
   let images = ['personal/aga naga.png',
'personal/comic cover.png',
'personal/fox.png',
'personal/glitch ratio.png',
'personal/intern(dark).png',
'personal/jigarthanda 2.png',
'personal/johnwick 1080.png',
'personal/joji.png',
'personal/kamal.png',
'personal/poem.png',
'personal/product 2.png',
'personal/product1.png',
'personal/rambo red.png',
'personal/rambo white.png',
'personal/red-bg-pixelated.png',
'personal/sdid.png',
'personal/sms.png',
'personal/Untitled-1.png',
'personal/Untitled-1(2).png',
'personal/vainko.png',
'personal/vv.png',
'personal/white.png',
'personal/WOW.png'
]

let images2 = ['College/1.png',
'College/3.png',
'College/4.png',
'College/arg.png',
'College/cosplaybw.png',
'College/hikaru no matsuri.png',
'College/hikaru no matsuricont3.png',
'College/mockup 1.png',
'College/mockup 2.png',
'College/movie mania_cover.png'
]

let images3 = ['Professional/1(3).png',
'Professional/BIA modules.png',
'Professional/c1.png',
'Professional/c2.png',
'Professional/c3.png',
'Professional/c4.png',
'Professional/COSMchair3.png',
'Professional/flyer back3.png',
'Professional/flyer front 2.png',
'Professional/Frame 247.png',
'Professional/Frame 520.png',
'Professional/Frame 552.png',
'Professional/Group 362.png',
'Professional/its hit.png',
'Professional/pod.png',
'Professional/Slice 7.png'
]
</script>
<div class = "flex items-center justify-center h-[80vh]">
    <div class = "mt-5 place-self-center flex flex-col justify-center h-fit p-6 border border-slate-400 gap-5">
        <div>
            <p class = "font-semibold">Personal Projects</p>
            <div class = "flex w-[90vw] overflow-scroll gap-4 rounded-md">
                {#each images as image}
                <img src={image} alt = "personal" class = "h-32"/>
                {/each}
            </div>
        </div>
        <div>
            <p class = "font-semibold">College Events</p>
            <div class = "flex w-[90vw] overflow-scroll gap-4 rounded-md">
                {#each images2 as image}
                <img src={image} alt = "personal" class = "h-32"/>
                {/each}
            </div>
        </div>
        <div>
            <p class = "font-semibold">Professional Works</p>
            <div class = "flex w-[90vw] overflow-scroll gap-4 rounded-md">
                {#each images3 as image}
                <img src={image} alt = "personal" class = "h-32"/>
                {/each}
            </div>
        </div>
    </div>
</div>