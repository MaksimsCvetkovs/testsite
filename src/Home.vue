<template>
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

        <h1>Map</h1>

        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d942.7529627173856!2d24.10424267801737!3d56.953113115476405!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x46eecf7bac058ce9%3A0x96a8a0e931b27448!2z0KDQuNC20YHQutC40Lkg0LPQvtGB0YPQtNCw0YDRgdGC0LLQtdC90L3Ri9C5INGC0LXRhdC90LjQutGD0Lw!5e1!3m2!1sru!2slv!4v1663829061215!5m2!1sru!2slv" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

        <h1>Vidio</h1>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</template>