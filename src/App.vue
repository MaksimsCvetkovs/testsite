<script setup>
</script>

<template>
  <div class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container">
            <a class="navbar-brand" href="#">Navbar</a>
            <div class="collapse navbar-collapse" id="navbarText">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Text1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Text1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Text1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Text1</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <div class="container py-5">
        <h1>Table</h1>

        <table class="table">
            <thead>
                <th>A</th>
                <th>B</th>
                <th>C</th>
                <th>D</th>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>2</td>
                    <td>3</td>
                    <td>4</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>3</td>
                    <td>4</td>
                    <td>5</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>4</td>
                    <td>5</td>
                    <td>6</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>5</td>
                    <td>6</td>
                    <td>7</td>
                </tr>
            </tbody>
        </table>

        <h1>Form</h1>

        <div class="row">
            <div class="col-auto">
                <label for="firstname" class="form-label">Firstname</label>
                <input class="form-control" id="firstname">
            </div>
            <div class="col-auto">
                <label for="seconame" class="form-label">Secondname</label>
                <input class="form-control" id="seconame">
            </div>
        </div>
        <div class="mb-3">
            <label for="email" class="form-label">E-mail</label>
            <input type="email" class="form-control" id="email">
        </div>

        <h1>Grid</h1>

        <div class="row">
            <div class="col-2">Text 1</div>
            <div class="col-2">Text 2</div>
            <div class="col-2">Text 3</div>
            <div class="col-2">Text 4</div>
            <div class="col-2">Text 5</div>
            <div class="col-2">Text 6</div>
        </div>
        <div class="row">
            <div class="col-6">Text 7</div>
            <div class="col-4">Text 8</div>
            <div class="col-2">Text 9</div>
        </div>
    </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
