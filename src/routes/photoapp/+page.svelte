<title>Photo App</title> 
<h1>Photo App</h1>

<script>
    let image="https://picsum.photos/id/70/367/267"
    let photo="https://picsum.photos/id/88/367/267"
    let picture="https://picsum.photos/id/93/367/267"
    let images=[image,photo,picture]
</script>

<div class="photos">
    {#each images as img}
     <div class="image-wrapper">
        <img src={img} alt="flexbox rules">
     </div>
        
    {/each}
</div>


<style>
    .photos{
    display:flex;
    flex-wrap: wrap;
    max-width: 300px;
    align-items: center;
    justify-content: space-around;
    }

    .photos img {
max-width: 100%;
}

.image-wrapper img {
max-width: 100%;
flex:1;
padding: 5px;
}
    </style>            