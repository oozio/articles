<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" lg="8">
        <div class="blog-hero">
          <!--- <img src="images/blog-image.jpg" alt="Full width blog image" />-->
          <h1>Progress Post: 27th of February 2020</h1>
        </div>

        <h3>A busy start</h3>

        <p>
          Phew! What a week.<br />
          <br />
          We&rsquo;ve gone from two researchers and a
          <b
            ><a
              href="https://forum.effectivealtruism.org/posts/8chk6DHZXctGHtNoz/covid-19-risk-assessment-app-idea-for-vetting-and-discussion"
              >forum post</a
            ></b
          >
          to a team of over a dozen, with expert academic advice and support
          rolling in.<br />
          As you may expect, much of our effort has gone into keeping on top of
          the organisational aspects of the project: onboarding new members,
          settling on a structure, and taking inventory of which specialities we
          have and which we still need. This process is still very much ongoing
          (keep an eye on our collaboration page for updates as we work out who
          else we&rsquo;re looking for!) but we&rsquo;re beginning to transition
          towards development of a proof-of-concept. At the same time,
          we&rsquo;re getting a better grasp of what is and isn&rsquo;t feasible
          and adjusting accordingly.
        </p>

        <p>
          A very rough timeline at this point is to have the basic components
          (GPS-based temporal heatmaps, epidemiological modelling, etc)
          understood and prototyped by the end of Monday the 2nd of March, and a
          functional proof-of-concept putting them all together within a week
          from then. Beyond that, we&rsquo;re aiming to have a final, polished,
          deployed app within three to four months, although this early on any
          figures are speculative at best.
        </p>

        <h3>Challenges</h3>

        <p>
          The technical challenges we&#39;re facing are complex - expect a post
          on them in the next day or so. In addition, there are several more
          abstract questions to work through. You can think of them as questions
          about <b>what</b> to do, while the technical questions are more
          focused on <b>how</b> to do it.<br />
          Some of these questions are:
        </p>

        <p>
          (1) How do we balance privacy and functionality? We want our heatmaps
          to be fuzzy to mask individual identities, but <b>how</b> fuzzy is an
          open question. Too specific and you make it trivially easy to track
          exactly where infected persons live, too vague and you get
          &ldquo;Someone in your country is sick, I hope that helps&rdquo;. At
          the moment we&rsquo;re considering a resolution of about 500 metres to
          a kilometre, which should be enough to preserve privacy (at least in
          urban areas) but that&rsquo;s very open to change as we test ideas
          out.
        </p>

        <p>
          (2) How do we enforce the privacy level that we settle on? Data
          re-identification is a very real concern for anybody who values their
          privacy, and we take the anonymity of our users seriously. Luckily for
          us, the security community has already put significant thought and
          effort into the issue - we&rsquo;re confident we can take advantage of
          this in the coming weeks, and are actively looking to work with
          experienced security researchers on the issue.
        </p>

        <p>
          (3) What legal issues do we need to consider? This project sits at the
          intersection of several complex legal issues: tracking, personal
          health information, and anonymity, to name a few. These issues
          won&rsquo;t have a dramatic effect on our immediate plan, but
          they&rsquo;re certainly something to address well before we start
          moving towards deployment. To further complicate the issue, while
          COVID-19 may be international, these laws aren&rsquo;t - different
          jurisdictions treat these issues differently.
        </p>

        <p>
          (4) Web app or mobile app? There are pros and cons to each - which may
          well be the topic of an upcoming post. Web apps are often cheaper to
          develop and easier to use, but don&rsquo;t always offer the same
          functionality that a mobile app can.
        </p>

        <p>
          (5) Which licensing system should we use? We&#39;re unanimously in
          favour of being completely open-source, but there are many different
          licenses to choose from, and each of them has slightly different
          implications. Again, this isn&#39;t a question requiring an immediate
          answer, but it will be important eventually - and it would most likely
          be easier to sort out now than after we&#39;ve developed a significant
          codebase.
        </p>

        <p>
          We don&rsquo;t have all the answers yet - but knowing which questions
          to ask is a good start.<br />
          If you think you might be able to help us out, check out our
          <b><nuxt-link to="/collaborate">collaborations</nuxt-link></b>
          page or contact us directly at
          <b
            ><a href="mailto: contact@covid-watch.org"
              >contact@covid-watch.org</a
            ></b
          >; and if you just want more updates, sign up to the newsletter below.<br />
          <br />

          Thanks for reading, and don&rsquo;t forget to wash your hands!<br />
          - The COVID-19 Risk App team
        </p>
        <SubscribeForm></SubscribeForm>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  import SubscribeForm from '../../components/SubscribeForm.vue'

  export default {
    components: {
      SubscribeForm
    }
  }

</script>