<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" lg="8">
        <section class="text-content">
          <div class="container">
            <div class="blog-hero">
              <h1 style="color:#BF3F4A">Blog Posts</h1>

              <div class="blog-item">
                <div class="blog-item-content">
                  <h2>Summary Article: 20th of March 2020</h2>

                  <p>
                    Rather than an ordinary blog post, this is what much of our
                    team have been working on for most of the past week. This is
                    a comprehensive summary of our project, now named COVID
                    Watch.
                  </p>
                  <p>
                    It covers the what, why, how, when, and where of this
                    project in detail, as well as discusses our progress so far.
                    The aim of doing so is to assist interested parties and
                    organisations in becoming familiar with the project in its
                    entirety. If that sounds like you, this is the place to
                    start.
                  </p>

                  <p>
                    This article is current as of the 20th of March, 2020.<br />
                    <nuxt-link class="read-more" to="/article"
                      >Read More...</nuxt-link
                    >
                  </p>
                </div>
              </div>

              <div class="blog-item">
                <div class="blog-item-content">
                  <h2>Bluetooth Primer: 7th of March 2020</h2>

                  <p>
                    This project is now roughly two and a half weeks old, and in
                    that time we&#39;ve made significant progress - not just
                    into solving the problems we&#39;d begun with, but in
                    understanding which problems we should be trying to solve in
                    the first place. We have a far deeper understanding of the
                    technologies and challenges.
                  </p>

                  <p>
                    At the same time, with the number of confirmed COVID-19
                    cases now over 100 000...<br />
                    <nuxt-link class="read-more" to="/blog/bluetooth"
                      >Read More...</nuxt-link
                    >
                  </p>
                </div>
              </div>

              <div class="blog-item">
                <div class="blog-item-content">
                  <h2>Insight Post: 6th of March 2020</h2>

                  <p>Welcome to our second insight post!</p>

                  <p>
                    Today&#39;s post comes from Tina White, a PhD candidate from
                    Stanford University specialising in applied machine learning
                    research. She&#39;s the main organiser here at the COVID-19
                    Risk App: the below post is a lightly edited version of an
                    internal document. Much of the technical content mentioned
                    has been covered in other blog posts: instead, the insight
                    here is how our project organises and plans...<br />
                    <nuxt-link class="read-more" to="/blog/insight2"
                      >Read More...</nuxt-link
                    >
                  </p>
                </div>
              </div>

              <div class="blog-item">
                <div class="blog-item-content">
                  <h2>Progress Post: 4th of March 2020</h2>

                  <p>
                    The big news first: we have a proof of concept!<br />
                    It takes multiple GPS trajectories and runs multiple
                    epidemiological simulations on them based on an assumption
                    of proximity-based transmission and our latest information
                    about COVID-19. It uses these simulations to generate a risk
                    heatmap...<br />
                    <nuxt-link class="read-more" to="/blog/progress2"
                      >Read More...</nuxt-link
                    >
                  </p>
                </div>
              </div>

              <div class="blog-item">
                <div class="blog-item-content">
                  <h2>Insight Post: 28th of February 2020</h2>

                  <p>
                    Welcome to our first insight post!<br />
                    In this series, our researchers will share what they&#39;re
                    currently working on and the challenges they&#39;re facing.
                    They will be more technical than our progress posts, but as
                    the name suggests they will hopefully provide some insight
                    into the state of the project.<br />
                    Today&#39;s post comes from James Petrie...<br />
                    <nuxt-link class="read-more" to="/blog/insight1"
                      >Read More...</nuxt-link
                    >
                  </p>
                </div>
              </div>

              <div class="blog-item">
                <div class="blog-item-content">
                  <h2>Progress Post: 27th of February 2020</h2>

                  <div class="blog-item-excerpt">
                    Phew! What a week.<br />
                    We&rsquo;ve gone from two researchers and a
                    <b
                      ><a
                        href="https://forum.effectivealtruism.org/posts/8chk6DHZXctGHtNoz/covid-19-risk-assessment-app-idea-for-vetting-and-discussion"
                        >forum post</a
                      ></b
                    >
                    to a team of over a dozen, with expert academic advice and
                    support rolling in.<br />
                    As you may expect...
                  </div>
                  <nuxt-link class="read-more" to="/blog/progress1"
                    >Read More...</nuxt-link
                  >
                </div>
              </div>
            </div>
          </div>
        </section>
      </v-col></v-row
    ></v-container
  >
</template>
