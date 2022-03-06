<template>
  <div class="whole">
    <div class="testimonials">
      <div class="card">
        <header class="class__header">
          <img src="images/image-daniel.jpg" class="card__img" alt="" />
          <div>
            <h3>Daniel Clifford</h3>
            <p>Verified Graduate</p>
          </div>
        </header>
        <p class="card__head">
          I received a job offer mid-course, and the subjects I learned were
          current, if not more so, in the company I joined. I honestly feel I
          got every penny's worth.
        </p>
        <p class="card__quote">
          "I was an EMT for many years before I joined the bootcamp. I've been
          looking to make a transition and have heard some people who had an
          amazing experience here. I signed up for the free intro course and
          found it incredibly fun! I enrolled shortly thereafter. The next 12
          weeks was the best - and most grueling - time of my life. Since
          completing the course, I've successfully switched careers, working as
          a Software Engineer at a VR startup."
        </p>
      </div>

      <div class="card">
        <header class="card__header">
          <img src="images/image-jonathan.jpg" class="card__img" alt="" />
          <div>
            <h3>Jonathan Walters</h3>
            <p>Verified Graduate</p>
          </div>
        </header>
        <p class="card__head">
          The team was very supportive and kept me motivated
        </p>
        <p class="card__quote">
          "I started as a total newbie with virtually no coding skills. I now
          work as a mobile engineer for a big company. This was one of the best
          investments I've made in myself."
        </p>
      </div>

      <div class="card">
        <header class="card__header">
          <img src="images/image-jeanette.jpg" class="card__img" alt="" />
          <div>
            <h3>Jeanette Harmon</h3>
            <p>Verified Graduate</p>
          </div>
        </header>
        <p class="card__head">An overall wonderful and rewarding experience</p>
        <p class="card__quote">
          "Thank you for the wonderful experience! I now have a job I really
          enjoy, and make a good living while doing something I love."
        </p>
      </div>

      <div class="card">
        <header class="card__header">
          <img src="images/image-patrick.jpg" class="card__img" alt="" />
          <div>
            <h3>Patrick Abrahms</h3>
            <p>Verified Graduate</p>
          </div>
        </header>
        <p class="card__head">
          Awesome teaching support from TAs who did the bootcamp themselves.
          Getting guidance from them and learning from their experiences was
          easy.
        </p>
        <p class="card__quote">
          "The staff seem genuinely concerned about my progress which I find
          really refreshing. The program gave me the confidence necessary to be
          able to go out in the world and present myself as a capable junior
          developer. The standard is above the rest. You will get the personal
          attention you need from an incredible community of smart and amazing
          people."
        </p>
      </div>

      <div class="card">
        <header class="card__header">
          <img src="images/image-kira.jpg" class="card__img" alt="" />
          <div>
            <h3>Kira Whittle</h3>
            <p>Verified Graduate</p>
          </div>
        </header>
        <p class="card__head">
          Such a life-changing experience. Highly recommended!
        </p>
        <p class="card__quote">
          "Before joining the bootcamp, I've never written a line of code. I
          needed some structure from professionals who can help me learn
          programming step by step. I was encouraged to enroll by a former
          student of theirs who can only say wonderful things about the program.
          The entire curriculum and staff did not disappoint. They were very
          hands-on and I never had to wait long for assistance. The agile team
          project, in particular, was outstanding. It took my learning to the
          next level in a way that no tutorial could ever have. In fact, I've
          often referred to it during interviews as an example of my developent
          experience. It certainly helped me land a job as a full-stack
          developer after receiving multiple offers. 100% recommend!"
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@200;300;400;700&display=swap');

* {
  margin: 0;
  padding: 0;
}
.whole {
  margin-left: 14rem;
}
body {
  background: #edf2f8;
  font-family: 'Barlow Semi Condensed', sans-serif;
  line-height: 1.7;
  font-size: 14px;
}

.testimonials {
  max-width: 1440px;
  margin-top: 1.5em auto;
  padding: 2em;
  box-shadow: rgba(17, 12, 46, 15%) 0px 48px 100px 0px;
  margin-bottom: 10px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 30px;
}

.card {
  background: #fff;
  border-radius: 10px;
  padding: 30px;
  box-shadow: rgba(17, 12, 46, 0.15) 0px 48px 100px 0px;
  margin-bottom: 10px;
}

.card__head {
  font-size: 1.5rem;
  font-weight: 500;
  line-height: 1.3;
  margin-bottom: 20px;
}

.card__header {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.card__header h3 {
  font-size: 15px;
}

.card__img {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  border: 2px solid #996ed9;
  margin-right: 10px;
}

.card:nth-of-type(1) {
  grid-column: 1 / 3;
}

.card:nth-of-type(4) {
  grid-column: 2 / 4;
  grid-row: 2;
}

.card:nth-of-type(5) {
  grid-column: 4;
  grid-row: 1 / 3;
}

@media (max-width: 768px) {
  .testimonials {
    grid-template-columns: 1fr;
    width: 100%;
  }

  .card:nth-of-type(1) {
    grid-column: 1;
  }

  .card:nth-of-type(4) {
    grid-column: 1;
    grid-row: 4;
  }

  .card:nth-of-type(5) {
    grid-column: 1;
    grid-row: 5;
  }
}
</style>
