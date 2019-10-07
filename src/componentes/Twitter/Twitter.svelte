<script>
    import IconoTwitter from "./Iconos/IconoTwitter.svelte";
</script>

<style>

        /* * {
            outline: 1px solid blue;
        } */

        article {
            max-width: 360px;
            height: 30rem;
            background-color: rgb(201, 185, 185);
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

        .Acerca {
            padding: 0 2rem;
        }

        .Tweets {
            width: 100%;
            max-height: 22rem;
            overflow: auto;
            color: #5E5E5E;
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
            flex-direction: row;
            flex-wrap: nowrap;
            justify-content: space-between;
            align-items: center;
        }

        .IconoTwitter {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 1;
        }

        .TituloTwitter {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 1;
        }
        
    
</style>
    
<article class="ContenedorTwitter">
    <header class="Encabezado">
    <div class="ContenedorEncabezado">
        <figure class="IconoTwitter">
            <IconoTwitter/>
        </figure>
        <div class="TituloTwitter">
            <h3>Activismo lingüístico</h3>
        </div>
        <figure class="IconoCerrar">
           <i>icon</i>
        </figure>
    </div>
    </header>
    <div class="Acerca">
        
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