<template>
  <div id="sigmie-search-box">
    <input type="text" name="search" id="search-box" />
    <div id="results">
      <div id="list">list</div>
      <div id="preview">preview</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
input[type="text"] {
  width: 200px;
  padding: 0.5rem;
  border-radius: 5px;
  border: 1px solid #edf2f7;
}

#list {
  display: inline-block;
}

#preview {
  display: inline-block;
}

#results {
  width: 200px;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1),
    0 2px 4px -1px rgba(0, 0, 0, 0.06);
}
</style>