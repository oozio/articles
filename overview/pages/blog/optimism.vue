<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" lg="8">
        <section class="text-content">
          <div class="container">
            <div class="blog-hero"></div>

            <h1 style="color:#BF3F4A">Together, We Can Beat COVID-19.</h1>

            <p>
              From a technical perspective, pandemics present a complex
              challenge. There are many different goals, sometimes competing,
              that we want to achieve as well as we can. In the case of
              pandemics, we want to prevent panic, avoid disruption to
              people&#39;s lives as much as possible, preserve civil and human
              rights, limit the economic impact - and, above all else, save
              lives.<br />
              <br />
              This type of problem - with many different outcomes which must be
              balanced - is known as an <em>optimisation </em>problem. These
              outcomes are the criteria by which we must judge interventions,
              directly or indirectly - including our own. Do we prevent panic
              and disruption?&nbsp; Preserve rights?&nbsp; Lower costs?<br />
              <br />
              Most importantly, <em>will this save lives?</em>
            </p>

            <p>We believe the answer to all of these questions is yes.</p>

            <p>
              Non-pharmaceutical approaches to limiting the spread of disease
              generally have two components:
            </p>

            <p>
              <strong>Filtering</strong>: Identifying <em>which </em>people are
              impacted, followed by
            </p>

            <p>
              <strong>Intervention</strong>: Modifying the behaviour of these
              people.
            </p>

            <p>
              For example, quarantining patients with a positive diagnosis
              applies a filter based on testing and then applies the quarantine
              intervention. Other examples include travel restrictions for
              at-risk areas, cancelling public events in a specific city, or
              encouraging more handwashing in an entire country.
            </p>

            <p>
              In the case of COVID-19, the main interventions are testing and
              self-isolation for a period of at least 14 days (the incubation
              period of the virus). Isolation and testing are incredibly
              powerful measures: they&#39;re regularly used to stop other
              infectious diseases in their tracks, and they&#39;re currently our
              best shot at slowing or stopping COVID-19 around the world.
            </p>

            <p>
              The downside is that they are also costly to use. If the filtering
              process is not accurate this could result in a huge number of
              false positives, and therefore a huge cost incurred in the form of
              negative impact on peoples&rsquo; lives: many people cannot earn a
              living in that two weeks, and many people have family or community
              obligations they would be unable to fulfill. Even that large cost,
              however, pales in comparison to the benefits. Every individual who
              fully self-isolates to avoid potentially getting infected and
              continuing a transmission chain can be expected to, on average,
              prevent 1 hospitalization for every 4 days of self-isolation. Even
              on a purely monetary basis, US households spend about $400/week on
              discretionary economic activity, whereas 1 hospitalization costs
              about $10,000. In other words, accurate self-isolation saves
              strained medical systems by allowing them to save beds, personnel,
              and often limited funds, allowing them to treat more people more
              effectively.
            </p>

            <p>
              The importance of a good filter is therefore two-fold: it limits
              the cost of false positives by ensuring that the only people
              self-quarantining are those who need to, and means that those
              people who <em>are </em>told to self-quarantine can be more
              confident that they really are high-risk, potentially increasing
              compliance.
            </p>

            <p>
              The gold standard filter is directly testing for the presence of
              COVID-19. Unfortunately testing kits are in short supply and not
              everybody can be tested, while those who are often have to wait
              hours or even days for the results.
            </p>

            <p>
              Instead, one commonly used measure is <em>contact tracing</em>:
              reconstructing the movements of infected individuals and
              identifying which people they came into contact with during the
              time they were contagious. In the case of COVID-19,
              epidemiologists have
              <a
                href="https://www.thelancet.com/journals/langlo/article/PIIS2214-109X(20)30074-7/fulltext"
                >calculated</a
              >
              that with 80% contact tracing accuracy and an average of 3.8 days
              between the onset of symptoms and detection of the virus,
              containment is very likely.
            </p>

            <p>The question for us, then, is this:</p>

            <p style="text-align: center;">
              <strong
                >&ldquo;Can an effective contact tracing program reduce local
                transmission so that sustained local spread does not
                occur?&rdquo;</strong
              >
            </p>

            <p>
              The answer seems to be yes. With a comprehensive testing program,
              high contact tracing accuracy, and self-isolation of diagnosed
              individuals, our models predict that each new case will likely
              cause on the order of 10 other cases before the outbreak is
              extinguished. It should be noted that not everything is known
              about this disease yet and models are never perfect. But it seems
              probable that this can be done, especially based on the recent
              success China has seen.
            </p>

            <p>
              So for people asking &ldquo;what happens next?&rdquo;, the options
              are not just global containment or infection of a majority of the
              world. We have a third option.
            </p>

            <p>
              What we need to do is build a system that is capable of rapidly
              containing local transmission. By doing this we can continue to
              interact with the rest of the world and any newly introduced cases
              will at most cause a small number of local infections. Even in the
              scenario where global containment fails and a vaccine isn&rsquo;t
              developed for years we can prevent the majority of the local
              population from getting sick.
            </p>

            <p>
              We believe that technology can be an important part of this
              solution. In order to remain operational for years, the contact
              tracing system must have a low social and economic cost. Mobile
              technologies can provide instantaneous and high accuracy contact
              tracing, even between strangers. Instead of requiring thousands of
              healthcare workers to do this manually (as is the current approach
              in China) the process will be essentially cost-free. Because the
              system will be so accurate, a majority of people can continue to
              live their lives without the need for increased social distancing.
            </p>

            <p>
              What we are developing is a high-quality filter to be used for the
              pandemic optimization problem. Combined with a comprehensive
              testing program, our filter may be powerful enough to protect our
              communities from COVID-19 becoming endemic.
            </p>

            <p></p>
          </div>
        </section>
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