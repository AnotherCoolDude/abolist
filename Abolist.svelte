<script>
  let abos = [
    { name: "Netflix", cost: "10", interval: "monthly" },
    { name: "Swapfies", cost: "19,50", interval: "monthly" }
  ];
</script>

<style>
  ul {
    list-style-type: none;
  }
</style>

<ul>
  {#each abos as abo}
    <li>{abo.name} costs you {abo.cost}€ {abo.interval}</li>
  {/each}
</ul>