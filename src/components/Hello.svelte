<script>
  export let name = 'World';
</script>

<style>
  .helloSvelte {
    text-align: center;
  }

  h4 {
    font-size: 20px;
    margin: 0 0 1em;
  }

  p {
    font-size: 14px;
    margin: 0;
  }

  p code {
    font-size: 1em;
    display: inline-block;
    background-color: #f5f5f5;
    padding: 0.5em 0.5em;
    border-radius: 3px;
  }
</style>

<div class="helloSvelte">

  <h4>Hello {name}!</h4>
  <p>
    Start building your app at
    <code>src/components/App.svelte</code>
  </p>

</div>
