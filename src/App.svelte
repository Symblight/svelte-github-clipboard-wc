<script context="module">
import '@github/clipboard-copy-element'
</script>


<script>
    export let name = "Alexis";
</script>
  <p>Hello {name}</p>


<clipboard-copy for="blob-path">
    <button>Copy</button>
</clipboard-copy>
<input id="blob-path" value="src/index.js">