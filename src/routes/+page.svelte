<h1>Boodschappenlijst</h1>
<p>Dit is om de API te testen.</p>

<script>
    const getItems = async () => {
        const res = await fetch('http://localhost:5006/api/Item');
        const itemJson = await res.json();
        console.log("Button clicked...");
        console.log(itemJson);
    }

    getItems();
</script>

