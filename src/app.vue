<template>
  <div id="app" class="container-fluid">
    <router-view />
  </div>
</template>
<style>
@import "https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css";
@import "https://use.fontawesome.com/releases/v5.7.2/css/all.css";
.container-fluid {
  height: 100vh;
}
.table thead tr th,
.table tbody tr td {
  padding: 0.2rem 0.5rem;
}
.tableResult {
  overflow: hidden;
  overflow-y: auto;
  height: 100%;
}
.border-radius-0 {
  border-radius: 0;
}
.form-group .form-text {
  margin-top: 0;
}
.form-group.is-invalid .form-control {
  border-color: #dc3545 !important;
}
.form-group.is-invalid .form-text {
  color: #dc3545 !important;
}
.alert {
  font-size: 0.8rem;
}
</style>

<script>
export default {
};
</script>