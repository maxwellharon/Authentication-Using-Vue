<template>
  <div class="event-card">
    <div class="card">
      <div class="card-content">
        <h2 class="is-size-4 has-text-weight-bold">{{ event.name }}</h2>
        <small class="event-date">{{ event.date }}</small>
        <span>{{ event.location }}</span>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: [
    'event'
  ]
}
</script>
