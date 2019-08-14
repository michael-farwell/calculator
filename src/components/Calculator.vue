<template>
    <b-row class="justify-content-center">
        <b-col sm="6">
            <b-card title="Current Value" class="text-right">
                <b-card-body>
                    <b-row class="mt-3">
                        <b-col sm="3">
                            <b-button>AC</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>C</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>+/-</b-button>
                        </b-col>
                        <b-col sm="3">
                        </b-col>
                    </b-row>
                    <b-row class="mt-3">
                        <b-col sm="3">
                            <b-button>7</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>8</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>9</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>+</b-button>
                        </b-col>
                    </b-row>
                    <b-row class="mt-3">
                        <b-col sm="3">
                            <b-button>4</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>5</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>6</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>-</b-button>
                        </b-col>
                    </b-row>
                    <b-row class="mt-3">
                        <b-col sm="3">
                            <b-button>1</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>2</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>3</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>X</b-button>
                        </b-col>
                    </b-row>
                    <b-row class="mt-3">
                        <b-col sm="3">
                            <b-button>0</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>.</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>=</b-button>
                        </b-col>
                        <b-col sm="3">
                            <b-button>/</b-button>
                        </b-col>
                    </b-row>
                </b-card-body>
            </b-card>
        </b-col>
    </b-row>
</template>

<script>
  export default {};
</script>

<style scoped>
    button {
        width: 100px;
        height: 100px;
        font-size: 24pt;
        margin: 0;
    }

    button.zero {
        width: 200px;
    }
</style>
