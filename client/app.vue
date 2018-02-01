<template>
    <div>
        App Stuff<br>
        bar: {{bar}}
    </div>
</template>

<script>
const bar = require('./bar.js')
export default {
    name: 'app',
    data() {
        return {
            bar: bar,
        }
    },
}
</script>