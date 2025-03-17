<script>
    import homePageImage from '$lib/images/dishes/Bibimbap.png'
</script>
<main>
    <section class="section-container">
        <h4 class="heading">You've Got Questions.</h4>
        <h4 class="heading">We've Got Taste.</h4>
        <p class="taste">
            Explore your Taste with special food in the special place. This text don’t have any meaning
        </p>
        <button class="order-now">order now</button>

        <div class="circle">
            <img class="home-image" src={homePageImage} alt="Bibimbap" srcset="">
        </div>
    </section>
    <section>

    </section>
</main>

<style lang="scss">
    .section-container {
        font-style: normal;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 1.5rem;
        gap: 16px;

        .heading {
            font-family: 'Alice';
            font-weight: 400;
            font-size: 32px;
            line-height: 37px;
            text-align: center;
            letter-spacing: -0.005em;
            color: #23262F;
            margin: 0;
        }
        .taste {
            font-family: 'Poppins';
            font-weight: 400;
            font-size: 18px;
            line-height: 27px;
            display: flex;
            align-items: center;
            text-align: center;
            color: var(--color-neutral-4);
        }
        .order-now {
            width: 117px;
            height: 36px;
            background: var(--color-primary-green);
            border-radius: 8px;
            font-family: 'Poppins';
            font-weight: 500;
            font-size: 14px;
            line-height: 20px;
            color: var(--color-neutral-8);
            text-transform: uppercase;
            cursor: pointer;
        }
        .circle {
            width: 100vw;
            height: 200px;
            background: #DDF3D8;
            border-top-left-radius: 29rem;
            border-top-right-radius: 29rem;
        }
        .home-image {
            position: relative;
            left: 6rem;
            bottom: 2rem;
            width: 50%;
        }
    }
</style>
