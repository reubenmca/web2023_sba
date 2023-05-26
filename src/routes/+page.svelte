
<div class="grid">

    <div class="card">
        <div class="image"></div>
        <div class="info">
            <h1 class="name">Evil Rick</h1>
            <h3 class="status"><div class="dead"></div> Dead - Humanoid</h3>

            <h3 class="locationLabel">Last known location</h3>
            <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
        </div>
    </div>

    <div class="card">
        <div class="image"></div>
        <div class="info">
            <h1 class="name">Evil Rick</h1>
            <h3 class="status"><div class="dead"></div> Dead - Humanoid</h3>

            <h3 class="locationLabel">Last known location</h3>
            <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
        </div>
    </div>

    <div class="card">
        <div class="image"></div>
        <div class="info">
            <h1 class="name">Evil Rick</h1>
            <h3 class="status"><div class="dead"></div> Dead - Humanoid</h3>

            <h3 class="locationLabel">Last known location</h3>
            <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
        </div>
    </div>

    <div class="card">
        <div class="image"></div>
        <div class="info">
            <h1 class="name">Evil Rick</h1>
            <h3 class="status"><div class="dead"></div> Dead - Humanoid</h3>

            <h3 class="locationLabel">Last known location</h3>
            <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
        </div>
    </div>

    <div class="card">
        <div class="image"></div>
        <div class="info">
            <h1 class="name">Evil Rick</h1>
            <h3 class="status"><div class="dead"></div> Dead - Humanoid</h3>

            <h3 class="locationLabel">Last known location</h3>
            <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
        </div>
    </div>

    <div class="card">
        <div class="image"></div>
        <div class="info">
            <h1 class="name">Evil Rick</h1>
            <h3 class="status"><div class="dead"></div> Dead - Humanoid</h3>

            <h3 class="locationLabel">Last known location</h3>
            <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
        </div>
    </div>

</div>

<script>
    let obj = {};
    let character_array = [];
    let BASE_URL = "https://rickandmortyapi.com";
        fetch(
        `${BASE_URL}/api/character/[1,2,3,4,5,6]`
    )
    .then((res) => res.json())
    .then((data) => {
        /*console.log(data)*/
        data.forEach((item) => {
            obj = {item};
            character_array.push(obj);
            character_array = [...character_array];
        });
    });
    
    character_array.forEach(item => {
        console.log(item);
    })

</script>