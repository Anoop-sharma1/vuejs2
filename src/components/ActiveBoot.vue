<template>
    <div>
        <h1>Active Boot</h1>

        <b-row>
    <b-col md="auto">
      <b-calendar v-model="value" @context="onContext" locale="en-US"></b-calendar>
    </b-col>
    <b-col>

      <pre class="small">{{ context }}</pre>
    </b-col>
  </b-row>
    </div>
</template>

<script>
export default {
    name : 'ActiveBoot'
}
</script>