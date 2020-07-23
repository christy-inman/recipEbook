<template>
    <div>
        <h1>TESTING</h1>
        <p>{{sampleMessage}}</p>
    </div>
</template>

<script>
export default {
  name: 'Test',
  props: {
      sampleMessage: String
  }
}
</script>