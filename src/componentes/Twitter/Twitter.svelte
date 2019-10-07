<script>
    import IconoTwitterVentana from "./Iconos/IconoTwitterVentana.svelte";
</script>

<style>

        /* * {
            outline: 1px solid blue;
        } */

        article {
            max-width: 360px;
            height: 30rem;
        }

        .ContenedorTwitter {
            max-width: 32%;
            display: flex;
            align-items: center;
            flex-direction: column;
        }

        .Encabezado {
            width: 100%;
            height: 5rem;
            background: #878787;;
            box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.1);
            border-radius: 10px 10px 0px 0px;
            margin-bottom: 1.5rem;
        }

        .ContenedorTweets {
            padding: 0 2rem;
        }

        .Tweets {
            width: 100%;
            max-height: 22rem;
            overflow: auto;
            font-style: normal;
            font-weight: normal;
            font-size: 1rem;
            line-height: 1.5rem;
            
            display: flex;
            flex-direction: column;
            align-content: space-around;
        }

        .ContenedorEncabezado {
            display: flex;
            padding: 0 2rem;
            flex-direction: row;
            flex-wrap: nowrap;
            justify-content: space-between;
        }

        
        .IconoTwitter {
            justify-content: flex-start !important;
            flex-basis: 60%;
            color: #fff;
            margin-left: -2.5rem;
        }

        .Activismo {
            display: flex;
            align-items: center;
            flex-basis: 125%;
            font-weight: 400;
            font-size: 1.4rem;
            line-height: 1.5rem;
            color: #fff;
        }

        .IconoCerrar {
            display: flex;
            flex-direction: column;
            color: #fff;
            justify-content: center;
            margin-right: -0.5rem;
        }



</style>
    
<article class="ContenedorTwitter">
    <header class="Encabezado">
    <div class="ContenedorEncabezado">
        <div class="IconoTwitter">
            <IconoTwitterVentana/>
        </div>
        <div class="Activismo">
            <span>
                Activismo lingüístico
            </span>
        </div>
        <div class="IconoCerrar">
           <i>icon</i>
        </div>
    </div>
    </header>
    <div class="ContenedorTweets">
        <div class="Tweets">
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente quod quidem delectus hic aspernatur sit eum rem laborum sequi, recusandae similique ut totam, dolores dignissimos veniam. Voluptatem error ipsam ipsa!
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Assumenda veritatis hic illo dolore a voluptate perspiciatis, beatae nisi odit distinctio maiores reiciendis corporis obcaecati veniam, illum possimus at? Delectus, vitae.
            </p>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit maxime quisquam optio quis aut nihil vero, ex fugiat non totam quidem modi, suscipit laboriosam molestiae placeat eligendi vel qui perspiciatis!
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit maxime quisquam optio quis aut nihil vero, ex fugiat non totam quidem modi, suscipit laboriosam molestiae placeat eligendi vel qui perspiciatis!
            </p>
            <p>
                Lore ipsum dolor sit amet consectetur adipisicing elit. Quo consequuntur autem repudiandae ducimus nobis possimus facere sunt sint vero laudantium ex aperiam ipsa a, beatae neque, nostrum dolor animi sit!
                Lore ipsum dolor sit amet consectetur adipisicing elit. Quo consequuntur autem repudiandae ducimus nobis possimus facere sunt sint vero laudantium ex aperiam ipsa a, beatae neque, nostrum dolor animi sit!
            </p>
        </div>
    </div>
</article>