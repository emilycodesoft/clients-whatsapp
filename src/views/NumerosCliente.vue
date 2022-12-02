<template>
  <FormCliente></FormCliente>
  <TableCliente></TableCliente>
</template>

<script>
import FormCliente from "@/components/FormCliente";
import TableCliente from "@/components/TableCliente";
export default {
  name: "numeros-cliente",
  components: { FormCliente, TableCliente },
};
</script>

<style>
</style>