<script>
    import Comments from './Comments.svelte'
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src="https://static.platzi.com/media/public/uploads/elmo002_25658817-f5c1-44b5-91c3-18f73d365073.jpg" alt="Elmo pug">
                <h2>
                Elmo.pug
                <span>Montevideo, Uruguay</span>
                </h2>
            </div>
            <div class="Card-settings">
                <i class="fas fa-ellipsis-h" />
            </div>
            <div class="Card-photo">
                <figure>
                    <img src="https://static.platzi.com/media/public/uploads/elmo002_25658817-f5c1-44b5-91c3-18f73d365073.jpg" alt="">
                </figure>
            </div>
            <div class="Card-icons">
                <div class="Card-icons-first">
                    <i class="fas fa-heart" />
                    <i class="fas fa-paper-plane" />
                </div>
                <div class="Card-icons-second">
                    <i class="fas fa-bookmark" />
                </div>
            </div>
            <div class="Card-description">
                <h3>renzit</h3>
                <span>Hola!</span>
            </div>
            <Comments />
        </div>
    </div>
</div>