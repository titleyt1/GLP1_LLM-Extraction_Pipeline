# GLP1_LLM-Extraction_Pipeline
Working appendix for thesis submission: From Reddit to Real World Evidence: Using LLMs to Decode Real World GLP-1 Patient Outcomes​

# Keywords:
  
lexical relevance: The relevance of a Reddit post determined by whether its text contains predefined terms associated with concepts of interest, used as an initial screen before LLM extraction.
  
seed terms: Predefined words or phrases grouped into concepts such as journey, weight, dose and experience, used to identify potentially relevant Reddit content.
  
baseline: The initial or reference measurement against which subsequent values or changes are compared.
  
canonicalise: To standardise different words, spellings or brand names referring to the same concept into a single consistent category for analysis.
  
Steroids/PEDs:Performance-enhancing drugs (PEDs) are substances used to enhance physical performance, muscularity or physique. In this study, PED reporting was treated as a potential confounding factor when comparing GLP-1 RA effects.
  
lean: Relating to body mass other than fat mass, or, when describing physique, having relatively low body fat with greater visible muscular definition.
  
prevalence: The proportion of authors within a specified group who reported a particular canonical adverse or desired effect at least once. Repeated reports of the same effect by one author were counted only once.
  
frequency: The number of times an event or effect occurs or is reported.
  
effects: Reported treatment related outcomes experienced by an author, classified in this study as adverse effects (AEs) or desired effects (DEs).
  
events: Individual, dated points within an author's reconstructed treatment timeline containing relevant first person information, such as dose, weight, effects, confounders, adherence or access information.
  
extraction fidelity: The degree to which information extracted by the LLM accurately reproduces the manually annotated source information.
  
chunking: Dividing long author journeys into smaller chronological blocks so they can be processed separately by the LLM before the extracted results are recombined. Journeys exceeding 60 posts were chunked into blocks of up to 60 posts.
  
reasoning effort: The configured level of model reasoning used before producing an output.
  
journey: The chronologically ordered collection of an individual author's Reddit posts or comments used to reconstruct their self reported treatment experience over time.
  
confounder: A factor associated with the population or exposure that may influence an observed relationship between a drug and reported outcome. PED use was investigated as a potential confounder in this study.
  
stratification: Dividing a cohort into subgroups according to a characteristic to enable comparisons between them, such as PED and non-PED authors.
  
pharmacovigilance: The detection, assessment, understanding and monitoring of adverse effects and other medicine-related safety information.
  
BH correction: Benjamini Hochberg correction: a multiple-testing procedure used to control the false discovery rate when statistical comparisons are performed.
  
Wilson confidence interval: A confidence interval (CI) for a proportion used to estimate the plausible range of the underlying prevalence, suitable in smaller samples or uncommon outcomes.
