<template>
  <div class="py-4 px-4">
    <h2>Mensaje</h2>
    <form action="" class="row">
      <textarea
        type="text"
        class="form-control"
        placeholder="Mensaje"
        style="height: 100px"
      />
      <div class="my-3">
        <label for="exampleInputEmail1" class="form-label">Media</label>
        <input type="file" class="form-control" />
        <!-- <div id="emailHelp" class="form-text">Imagen o Video.</div> -->
      </div>
      <button type="submit" class="mt-2 btn btn-success">
        Establecer mensaje
      </button>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>