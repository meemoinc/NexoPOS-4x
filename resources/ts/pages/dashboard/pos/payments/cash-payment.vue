<template>
    <sample-payment identifier="cash" label="Cash"></sample-payment>
</template>
<script>
import { default as samplePayment  } from "./sample-payment";
export default {
    name: 'cash-payment',
    components: {
        samplePayment
    }
}
</script>