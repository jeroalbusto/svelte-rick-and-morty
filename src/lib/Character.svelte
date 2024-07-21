<script>
    export let character
</script>

<div class="character">
    <img src={character.image} title={character.name} alt={character.name}>
    <h1>{character.name}</h1>
    <h3>{character.species}</h3>
</div>