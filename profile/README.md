# MyNuGen

MyNuGen focuses on data driven college admissions guidance.

Using machine learning and vector based profiling, we model both students and colleges in a shared multi dimensional space. Each student and each school is represented as a vector built from academics, extracurriculars, personal qualities, and fit or interest dimensions. Similarity and distance measures are then used to:

- Recommend colleges that are a strong academic and personal fit
- Estimate likelihood of admission (safety / target / reach)
- Show students how their profile is evolving over time as they work with coaches

Over time, college vectors are refined using actual admission outcomes so that the system better reflects what each school is looking for.

---

## Internal repositories

- `platform-tooling`  
  Internal engineering kits and utilities used across MyNuGen projects. This includes components such as the `pii_detector` pipeline for anonymizing admissions style documents before they are used in analytics or matching workflows.

Additional repositories will be added as the platform and services evolve.
