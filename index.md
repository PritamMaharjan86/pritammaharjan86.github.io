// ------------------------------------------------------
//   RENDERING <PRITAM /> ...
// ------------------------------------------------------

import React from "react";

const Pritam = () => {
  return (
    <Human version="1.0.0">
      <header>
        <Identity
          name="Pritam Maharjan"
          role="Software Engineer (Web)"
          email="primgdev@gmail.com"
          location="Sydney, Australia"
        />
      </header>

      <section title="about">
        <p>
          I write code the same way I learn — one component at a time.
          I enjoy small things that make big differences:
          clean structure, readable logic, and experiences
          that feel effortless for the user.
        </p>
      </section>

      <section title="philosophy">
        <p>
          const principles = [
            "clarity over complexity",
            "less code, more intention",
            "design is behaviour",
            "simplicity scales"
          ];
        </p>
      </section>

      <section title="stack">
        <Stack
          frontend=["Components", "State", "UI Logic"]
          backend=["APIs", "CMS Systems", "Performance Fixes"]
          tools=["Git", "Debugging", "Problem Solving"]
        />
      </section>

      <section title="journey">
        <Timeline>
          <Step at="Cypha Interactive">Shipped CMS features</Step>
          <Step at="GO Tech International">Improved platform stability</Step>
          <Step at="PIEX Education">Created interactive experiences</Step>
        </Timeline>
      </section>

      <section title="current">
        <p>
          return (
            <Growth>
              Learning deeper patterns.  
              Building cleaner UI.  
              Improving every commit.  
            </Growth>
          );
        </p>
      </section>

      <footer>
        <Contact email="primgdev@gmail.com" />
        <p>// end of render</p>
      </footer>
    </Human>
  );
};

export default Pritam;
