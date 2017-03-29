<script>
    export default {
        name: 'base-button',
        props: [],
        render( createElement ) {
            return createElement(
                'button',
                {
                    class: ['base-button']
                },
                this.$slots.default
            )
        },
        methods: {}
    }
</script>
<style>
    button.base-button {
        display: inline-block;
        padding: 0.5em 1em;
        cursor: pointer;
        box-sizing: border-box;
        border: 1px solid black;
        color: black;
        -webkit-border-radius: 4px;
        -moz-border-radius: 4px;
        border-radius: 4px;
        background-color: white;
    }
</style>