<template>
    <div class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container">
            <a class="navbar-brand" href="#" @click="$emit('switch', 'home')">Logo</a>
            <div class="collapse navbar-collapse" id="navbarText">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item" :class="{'active': page === 'home'}">
                        <a class="nav-link" href="#" @click="$emit('switch', 'home')">Home</a>
                    </li>

                    <li class="nav-item" :class="{'active': page === 'another-page'}">
                        <a class="nav-link" href="#" @click="$emit('switch', 'another-page')">Another Page</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        page: String,
    },
};
</script>