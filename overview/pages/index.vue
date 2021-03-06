<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" lg="10">
        <v-row align="center">
          <v-col cols="12" sm="5" style="display:flex;flex-direction:column;align-items:center;">
            <img
              width="100%"
              style="margin-right: 20px;border:1px solid gray;border-radius:2px;"
              alt="COVID Watch"
              src="~/assets/images/map2.png"
            />
            <p style="color:gray;font-size:1em">Hotspots of COVID-19 risk in our map demo (fake data)</p>
          </v-col>

          <v-col cols="12" sm="7">
            <h1 style="color:#BF3F4A">Our Mission</h1>
            <br />
            <h3>
              Slow the spread of infectious diseases like COVID-19 with
              crowdsourced data.
            </h3>
            <p>
              We are developing an app that shows individuals their risk of
              COVID-19 infection based off GPS data, known cases, and Bluetooth
              proximity networks. We aim to do so in a way that preserves
              transparency and personal privacy.
            </p>
          </v-col>
        </v-row>
        <br />

        <h2>Our Plan</h2>

        <p>
          We believe there&#39;s a non-trivial chance that GPS tracking or other
          sources of location information could reduce the spread of infectious
          diseases like COVID-19 by informing individuals of their risk and
          helping implement better self-quarantine measures. We also believe
          that this can be done in a way that doesn&#39;t sacrifice rights like
          privacy.
        </p>

        <p>
          We&#39;re a group of volunteers researching and designing an
          open-source app to make this idea a reality. Ideally, this app will
          take the GPS and Bluetooth data of users in an anonymised way, as well
          as some information about their potential or confirmed infection
          status, and use it to the benefit of both them and everybody else.
          There are several ways this could happen: through secure and anonymous
          contact tracing, through the creation of a risk
          <nuxt-link
            class="link"
            :to="{ path: '/article', hash: 'heatmapImplementation' }"
            >heatmap</nuxt-link
          >
          , and through more accurate epidemiological modelling.
        </p>

        <p>
          A more in-depth discussion of our plan is available
          <nuxt-link to="/article">here</nuxt-link>
        </p>
        <h2>We Can Make A Difference</h2>

        <h3>The Challenge</h3>

        <p>
          At this point, it is apparent that a strategy of pure containment will
          not work for COVID-19: with over 100 000 recorded cases globally, a
          perfect quarantine is functionally impossible. This does not, however,
          mean that widespread global infection is inevitable. There is a third
          option.
        </p>

        <p>
          What we need to do is build a system that is capable of rapidly
          containing local transmission, wherever and whenever it appears. By
          doing this, and implementing it in our communities, we can continue to
          interact with the rest of the world and any newly introduced cases
          will at most cause a small number of local infections. Even in the
          scenario where treatments options are limited and a vaccine
          isn&rsquo;t developed for years, we can prevent the majority of the
          population from getting sick.
        </p>

        <h3>The Solution</h3>

        <p>
          One main non-pharmaceutical interventions currently being used for
          COVID-19 globally is <em>contact tracing</em>. When somebody is found
          to have the virus, epidemiologists reconstruct their movements to
          identify who they may have been in contact with: in other words,
          people they may have infected. We believe that technology can be an
          important part of this solution. In order to remain operational for
          years, the contact tracing system must have a low social and economic
          cost. Mobile technologies can provide instantaneous and high accuracy
          contact tracing, even between strangers. Instead of requiring
          thousands of healthcare workers to do this manually (as is the current
          approach in China) the process will be essentially cost-free. Because
          the system will be so accurate, a majority of people can continue to
          live their lives without the need for increased social distancing.
        </p>

        <h3>Our Contribution</h3>

        <p>
          What we are developing is essentially a combination of two things.
          Firstly, it will act as a preventative: lowering the risk of infection
          by alerting users of high-risk areas. Secondly, and more significant,
          it is a high-quality, low-cost filter to aid contact tracing efforts
          and quickly identify at-risk individuals.
        </p>

        <p>
          Combined with a comprehensive testing program, our filter may be
          powerful enough to protect our communities from COVID-19 becoming
          endemic. That&#39;s a bold claim, but we
          <nuxt-link to="/optimism">firmly believe it can happen</nuxt-link>.
        </p>

        <h2>If We&#39;re Wrong</h2>

        <p>
          We&#39;re a competent team, and we like to think we know what
          we&#39;re doing. Even so, epidemiology is complex and the world can be
          a messy place. Perhaps some of our underlying assumptions about
          COVID-19 are incorrect, or our app requires some critical mass of
          adoption to be truly effective that we don&#39;t reach.
        </p>

        <p>
          We&#39;ve considered these scenarios, and designed with them in mind.
        </p>

        <p>
          Firstly, we&#39;re constantly monitoring the progress of COVID-19
          research and updating our assumptions accordingly, in close
          consultation with our
          <nuxt-link to="/advisors">academic advisors</nuxt-link>. If the
          research suggests that we&#39;re wildly off-track, we&#39;re open to
          making changes or reassessing the project as needed (although so far
          it&#39;s shown just the opposite). The end result is that if
          there&#39;s a more effective way to achieve our goals, we&#39;re in a
          good position to find it and pivot in that direction.<br />
          Secondly, we&#39;ve designed our app to be useful at a range of
          adoption levels. At ubiquitous adoption levels, our Bluetooth contact
          tracing work alone could halt COVID-19&#39;s spread. Even if we
          don&#39;t reach that goal, however, our heatmap functionality is
          designed to provide value to our users even at extremely low adoption
          rates. This ensures that even if we do fall short of our ultimate
          goal, we still capture the significant benefit of <em>slowing </em>the
          spread of the virus.
        </p>

        <p>
          This may not sound too impressive - if COVID-19 is going to become
          widespread anyway, why bother delaying the inevitable? The truth is
          that in reality, slowing the spread is still extremely useful: one
          major risk of COVID-19 is that it could overwhelm health systems,
          limiting their ability to care for people who desperately need it. By
          reducing infection rates we space cases out slowly enough that
          hospitals worldwide can deal with them as they come, saving lives.
        </p>

        <p style="text-align: center;">
          <img
            width="80%"
            alt="CC BY 2.0 Esther Kim &amp; Carl T. Bergstrom"
            src="~/assets/images/SlowPeaks.jpeg"
          />
        </p>

        <p>
          Even simply <em>delaying </em>the peak of the infections still has
          benefits. Across the planet, health agencies are ramping up production
          of testing kits and other essentials: every extra day that we can give
          them to prepare translates into lives saved.
        </p>

        <p>
          We&#39;re not there quite yet at the level of directly aiding these
          efforts - but we&#39;re close. By the end of March we aim to have a
          basic app ready to go to live, and with your support and cooperation,
          we can use it to beat this disease and keep our communities safe.
        </p>

        <p></p>

        <p></p>
        If you think you would like to help, see our
        <b><nuxt-link to="/collaborate">collaborate</nuxt-link> </b>
        page.

        <p></p>

        <p>
          For all inquiries, please contact us at
          <b
            ><a href="mailto: contact@covid-watch.org"
              >contact@covid-watch.org</a
            ></b
          >.
        </p>

        <p>
          Lastly, if you just want to stay in the loop, you can sign up to our
          newsletter for updates:
        </p>


        <SubscribeForm></SubscribeForm>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  import SubscribeForm from '../components/SubscribeForm.vue'

  export default {
    components: {
      SubscribeForm
    }
  }

</script>
