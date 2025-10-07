<template>
    <form>
        <div>
            <label for="nombre">Nombre</label>
            <input id="nombre" name="nombre" type="text"/>
        </div>

        <div>
            <label for="direccion">Direccion</label>
            <input id="direccion" name="direccion" type="text"/>
        </div>

        <div>
            <label for="edad">Edad</label>
            <input id="edad" name="edad" type="number"/>
        </div>

        <div>
            <button type="submit">Enviar</button>
        </div>
    </form>
</template>

<script>
export default {
    name: 'FormPage',
};
</script>