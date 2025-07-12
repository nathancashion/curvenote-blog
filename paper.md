---
title: Introduction
description: ''
short_title: ''
subtitle: What can telemedicine providers learn from live streamers?
tags: []
date: '2024-07-09'
oxa: oxa:tgSYYIag2qhHH1yPOHt4/YsqKiR3JykwsSu6fHCEC
keywords: []
---

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/rGH5HX8FHiUnR1uR8kDZ.3","tags":[],"part":"abstract"}

Telemedicine has rapidly emerged as a promising approach to managing back, neck, and other musculoskeletal (MSK) pain. Despite impressive advances in the technology, clinicians and patients remain reluctant to adopt it. The transition to telemedicine from hands-on, in-person care presents numerous barriers. In contrast, new technologies and tools are readily embraced by early-adopters in other industries, such as video game streaming, fitness influencers, and YouTube content creators. By adopting tools and techniques from these other industries, MSK providers may be able to increase in-session engagement and patient satisfaction with telemedicine.

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/QqnlNLnK7T5DzEvKhGiS.5","tags":[]}

# Introduction

Telemedicine has the potential to bring healthcare to millions of patients who are unable to visit their doctor. This holds true even in specialties that traditionally demand a face-to-face, such as chiropractic, osteopathy, physical therapy, and pain medicine. Surprisingly, these specialties focused on musculoskeletal conditions have also benefited from the use of telemedicine, particularly during the COVID-19 pandemic {cite:p}`lamplotGoodComesEvil2021`.

However, video calls leave much to be wanted, especially for conditions that are commonly examined and treated with direct, physical touch via physiotherapy, chiropractic, and massage. Patients and their clinicians observe feelings of disconnect during their live video calls {cite:p}`ahmadPatientPerspectivesTelemedicine2023`. Healthcare systems and private clinics have been slow to include telemedicine in MSK practice for various reasons, including cost, resistance to change, and lack of clarity on the benefits and feasibility in this specialty {cite:p}`daviesInternationalCoreCapability2021`. Learning how to make telemedicine a better experience for both patients and clinicians can accelerate the potential reach of this promising technology.

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/NglmIFFcOeRGm87InL7a.1","tags":[]}

```{iframe} https://www.youtube-nocookie.com/embed/Obq0FGVvbZ8
:align: center
:width: 70%
```

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/xOcCgoCvuF5GykrTz13A.3","tags":[]}

## Overview of Topic

\*Telemedicine\* is defined as the practice of caring for patients from a distance {cite:p}`jinTelemedicineCurrentImpact2020`. \*Telehealth\* is a broader term that can include population-based efforts in public and global health. In contrast, the focus of telemedicine is on a single patient or small group of patients {cite:p}`barberioTransitioningTelehealthTodays2021`. \*Telerehabilitation\* is another term that is often used interchangeably with telemedicine for musculoskeletal conditions, particularly physical therapy in post-surgical scenarios {cite:p}`baroniStateArtTelerehabilitation2023`. While the topic of this paper is focused on musculoskeletal applications, most of the concepts do apply to other specialties. Hence, I will use telemedicine throughout for consistency.

Telemedicine has been used in various forms for centuries (consider carrier pigeons being used to suggest tinctures for the plague or phone calls to the family doctor for a child's late-night stomachache) {cite:p}`jinTelemedicineCurrentImpact2020`. Modernly, it has become nearly synonymous with implementations via the internet, such as video conferencing calls between a provider and a patient {cite:p}`daviesInternationalCoreCapability2021`.

Telemedicine offers many benefits to patients, but legislation has not kept up with demand. As a result of the pandemic, legislation required insurance companies to pay for telemedicine visits with temporary exceptions allowing for greater access across state lines {cite:p}`barberioTransitioningTelehealthTodays2021`. However, while some aspects of this have been extended, it is unclear whether reimbursement will continue for all services across all specialties {cite:p}`TelehealthHereStay2021`. For telehealth to have a positive effect on healthcare, several challenges must be addressed in policy and research.

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/1gQ820sP2e19al8TiiqQ.3","tags":[]}

## Identification of Gap

Beyond the slow adjustments in legislation and reimbursements, telemedicine has suffered in hasty roll-outs that have not afforded optimal infrastructure or training to take place. In fact, one of the key factors in clinicians' reluctance to use telehealth is the lack of familiarity with the technology and ideal procedures for conducting virtual visits with patients {cite:p}`daviesInternationalCoreCapability2021`.

While most of us were forced to rapidly adapt to a Zoom-centered culture, using the same tools for different situations can lead to sub-optimal experiences. A conversation about low back pain, for example, is meant to be a dynamic collaboration between patient and provider, often including the use of visuals such as physical anatomical models to illustrate the underlying structures that may be associated with pain syndromes. Experiences like these are challenging to achieve in a 2-dimensional, relatively static video call when both participants are limited to showing themselves from the mid-torso to above the head. Even worse, Zoom meetings are often affected by quality issues such as poor-audio or bad lighting that make it difficult for the participants to understand one another, let alone forge an emotional connection. Problems with internet connectivity can interrupt a speaker mid-sentence or prevent a call from starting altogether.

Advances in audio and video technology, however, make it possible for amateurs and hobbyists to create high-quality video content, including well-produced, livestreaming video. Fitness influencers post ultra-high definition videos to educate and entertain their followers about healthcare topics on social media and YouTube. From the average bedroom – or their parents' basement – 'gamers' broadcast their video game activities to hundreds of thousands of engaged fans, using tools to create a dynamic and highly-produced experience that leaves viewers feeling like they are a part of a community.

Based on my review of the literature, there is little to no discussion about improving the technical aspects of synchronous telemedicine video calls and how they influence the patient and clinician experience. Pulling from the literature on user experience design, live video streaming, and incorporating skills from audio and video engineering, it is possible to greatly improve the experience and satisfaction of all involved.

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/DFLO5ILniG7WPzf5s2Ab.3","tags":[]}

# Background

## Selection of Topic

As a chiropractor with a passion for technology, I have been fascinated by the possibilities of providing spine care remotely, both via telemedicine or asynchronous media such as mobile apps and tools using artificial intelligence. Spurred on by the COVID-19 pandemic, telemedicine has become more common throughout all specialties, including for musculoskeletal conditions normally treated by chiropractors and physiotherapists {cite:p}`lamplotGoodComesEvil2021`. However, due to the hands-on nature of manual therapy offered as treatment for musculoskeletal aches and pains, patients and providers have expressed doubts as to the practicality of telemedicine {cite:p}`bartonItsSecondBest2022`. While physical therapies are prominent, other components of evidence-based musculoskeletal care include education and exercise prescription, both of which can be provided effectively via telemedicine solutions {cite:p}`baroniStateArtTelerehabilitation2023`.

Patients who opt for telemedicine visits have reported positive outcomes, even if they were initially skeptical \[@hinmanTelerehabilitationConsultationsPhysiotherapist2024; @lawfordWasReallyScepticalBut2018\]. According to @ernstzenYouMustUnderstand2022, patients experiencing chronic pain who joined a group exercise program found that it helped them feel empowered. Multiple studies have determined that for patients with musculoskeletal disorders, telemedicine is as safe and effective as in-person care \[@bargeriEffectivenessTelemedicineMusculoskeletal2024; @seronEffectivenessTelerehabilitationPhysical2021; @withersRemotelyDeliveredPhysiotherapy2024\].

Despite this early success, many barriers still exist that prevent more widespread adoption of telemedicine. Using a qualitative approach, @wadeClinicianAcceptanceKey2014 concluded that clinician acceptance is the leading factor limiting adoption of telemedicine, followed by patient acceptance. This reluctance is reflected in the previous findings that remotely delivered care does not meet the patient's expectation of hands-on touch \[@baroniStateArtTelerehabilitation2023\]. @saragiottoCanYouBe2022 commented on this paradox of being a manual therapist but not using your hands. While they found the existing literature on telemedicine was limited, the available evidence suggests that practitioners of manual therapies are able to have a positive effect on reducing pain and improving function in patients with musculoskeletal conditions in a virtual setting. Therefore, the authors recommended that manual therapists include telemedicine in their available options for treatment.

Other criteria for resistance to telemedicine include a lack of familiarity with the technology, referred to as \*digital literacy\* \[@fernandesWhatExtentCan2021; @manganelloRelationshipHealthLiteracy2017\], and the ability to build rapport and develop a therapeutic alliance between patient and practitioner \[@wallaceGroupIndividualTelehealth2022\].

This final point has captured my attention and imagination. What is it about the experience on video calls that has people feeling disconnected? What are the elements that lead to the so-called "Zoom fatigue" so many of us have experienced during the rapid shift to virtual communication during the pandemic \[@bailensonNonverbalOverloadTheoretical2021\]? Are there solutions that are already being used in other industries to increase the feeling of connectedness and engagement during telemedicine appointments?

Most research to date has evaluated the presence of telemedicine in care settings as well as the results in terms of patient outcomes and safety. But have researchers considered that \*how\* telemedicine visits are conducted may have an impact on the outcomes? In most other areas of technology, immense effort and millions of dollars are spent on refining the user-experience (UX) of digital tools and software to increase user satisfaction \[@monachelliDesigningMHealthApps2024\]. What changes could be made to the UX of telemedicine to increase patient satisfaction and decrease clinician burden?

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/xPZ6MdmHMIddXzFcdRwt.1","tags":[]}

## Literature Search

I conducted a series of searches using EBSCOHost. A broad search for \`"telehealth"\` returned 180,725 results. Adding the terms \`"telemedicine OR telehealth OR telerehab\*"\` reduced my results to 800+. I further limited the search to relevant papers using the term \`"musculoskeletal"\`. As technology is a rapidly advancing field, I limited the Publication Date to between 2019-2024. Source types were restricted to Academic Journals and Reviews.

Searches for \`"telehealth AND engagement"\` provided limited results relevant to the current topic. I conducted further searches via PubMed on engagement in live streaming applications, such as video games and ecommerce with the terms \`"live streaming AND engagement"\`. Results were varied and I narrowed the selection by scanning titles and abstracts for relevance, then reviewing related papers and papers cited by or citing the current paper.

I included other articles found via Google Scholar and Google Search that were relevant. Though they may not be peer-reviewed, they are authored by industry experts.

When new topics or keywords appeared frequently in my initial results, I explored them further by searching the same databases. I also used artificial intelligence research assistants \[@elicitElicitAIResearch2024; @researchrabbitResearchRabbit2024\] to suggest other articles or related topics.

### Literature Review

My literature brought together research in two broad areas—the use of telemedicine in musculoskeletal health and the psychology of engagement in live-streaming video.

A review of the existing literature on telemedicine in musculoskeletal care revealed a number of themes. The majority of the research addressed trends in the use of telemedicine broadly. This thread of the literature included prevalence of remote therapies as well as acceptance and perceptions by both clinicians and patients. The second most common theme in the research concerned the reliability of the examination and diagnosis of musculoskeletal disorders via telemedicine as well as the effectiveness of treatment. Other themes included the core competencies suggested for clinicians to conduct telemedicine visits and the limitations of telemedicine in practice.

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/5yfyrLkIFji5vZSdJqe9.3","tags":[]}

### Telemedicine in MSK care

\*Trends in use and acceptance of telemedicine\*

Out of necessity, the use of telemedicine accelerated during the global COVID pandemic. A Nature Medicine editorial reflects on the trajectory of telehealth during the COVID-19 pandemic \[@TelehealthHereStay2021\]. According to Medicare data, telehealth visits increased ten-fold in a 12-month period (from March 2020–March 2021).

Telemedicine is not only used for individuals. Several programs have explored adapting group programs for chronic pain to a virtual setting. @wallaceGroupIndividualTelehealth2022 conducted a scoping review of group and individual telehealth for chronic musculoskeletal pain to explore patient perspectives on virtually delivered pain management programmes. From 10 included studies, the authors extracted 4 themes: usability of the technology, tailored care, therapeutic alliance, and managing behavior. The authors determined that telehealth for chronic musculoskeletal pain is acceptable by patients. Group telehealth programs additionally offer opportunities for social support and validation of the pain experience. Patients felt empowered and intrinsically motivated to modify their behaviour. The authors discussed how clinicians can help develop a therapeutic alliance during telehealth interventions. This is more readily accomplished via synchronous video-conferencing rather than asynchronous messaging.

South Africa offers a group Patient Education Empowerment Programme (PEEP) for patients living with chronic pain. Due to the pandemic, this program was adapted to be delivered remotely via synchronous (group calls) and asynchronous (educational materials) methods. @ernstzenYouMustUnderstand2022 interviewed six women who participated in this 6-week telehealth group program to learn what worked and what didn't. The patients felt that the program helped them start on a journey of self-discovery and personal development. Connecting with other patients experiencing similar pain and disability helped validate their experiences and motivated them to alter their behaviors. Participants reported that this method of delivering a group program for chronic musculoskeletal pain was feasible and that they felt engaged and supported. Facilitators were able to develop a therapeutic alliance through virtual communication without meeting patients in person. While there were barriers to comfortably participating in this course, facilitators were able to address them with planning. For example, data packages were provided to patients to cover the cost of increased cellular data usage.

@ahmadPatientPerspectivesTelemedicine2023 surveyed nearly 500 patients who had received telemedicine care for hand surgery consultation during the pandemic. The majority of respondents liked their experience of a teleconsultation and felt satisfied with the attention recieved from their provider. Despite this, over two-thirds of the patients said they would still prefer an in-person visits when available. Common reasons for this choice included difficulty explaining their symptoms and the need for an in-person follow-up visit to move forward with their care.

\*Diagnosis and management of MSK conditions via telemedicine\*

@ohAgreementConcurrentValidity2024 reviewed 9 studies on the assessment and management of people with MSK conditions. They found that inter-rater reliability for diagnosis involving the low back, knee, shoulder, lower limb, ankle, elbow, and shoulder was high. The authors concluded that telehealth is a feasible option for assessment of musculoskeletal conditions.

@satinVirtualSpineExamination2021 provided a narrative review on how clinicians can conduct physical examination for spine-related disorders via virtual calls. The authors presented strategies for overcoming some of the difficulties unique to virtual examination of the spine.

A systematic review from @bernhardssonDigitalPhysiotherapyAssessment2023, compared face-to-face physiotherapy assessment of musculoskeletal disorders with convential assessment. Digital physiotherapy assessment was found to have moderate to almost perfect validity when compared to traditional physical exams. The authors explained that while patients thought an in-person assessment was better, they were satisfied with their experience. The reported outcomes also demonstrated excellent reliability of patient-reported outcome measures.

A study in India showed that telerehabilitation for spine pain reduced pain and disability better than standard in-clinic rehabilitation during the COVID pandemic \[@shahEfficacyTelerehabilitationSpine2024\]. As reported by @barberioTransitioningTelehealthTodays2021, an overview of clinical outcomes and patient satisfaction concluded that telemedicine offered equal or better results than usual care.

\*Core competencies for telemedicine in MSK\*

@daviesInternationalCoreCapability2021 conducted a modified Delphi survey ith experts in physiotherapy, including researchers, clinicians, consumers, and representatives of physiotherapy organizations. The panel developed a framework to outline the skills and capabilities needed to deliver care via video calls. The recommendations consisted of legal and ethical topics such as patient privacy & safety, record keeping, and licensure. The panel also outlined technical skills such as camera placement, software selection, and adapting the physical exam to a virtual setting.

@haldemanDistanceManagementSpinal2021 describe the process of developing a pair of guides to help clinicians and patients manage spinal pain during the COVID-19 pandemic or in any situation that requires management from a distance. A group of 29 individuals from 10 countries including experienced clinicians, researchers, and educators collaborated through an iterative process to create two guides. The Patient Guide includes 2 steps to help patients self-assess the severity and nature of their spinal pain and determine an appropriate course of action, such as emergency care, urgent care, or non-urgent communication with a healthcare provider. The Clinician Guide provides a framework for providers to systematically assess and classify patient's spinal disorders. The authors suggest that telehealth visits will provide a helpful method for patients and clinicians to evaluate and manage spinal disorders when face-to-face visits are not available.

\*Limitations of telemedicine\*

As telehealth becomes more popular and widespread, it is important to recognize the strengths and weaknesses of this new platform. While many clinicians and patients see the lack of hands-on care as a drawback \[@bartonItsSecondBest2022\], manual therapy is just one of many modalities that clinicians can use to manage patients with musculoskeletal conditions. Nevertheless, while physical touch isn't required in medicine, it is still appropriate to consider the inherent value in skin-to-skin contact.

@apathyTelemedicineInPersonVisit2024 recognize that providers offering telemedicine must change their workflow. The authors analyzed how much time clinicians in a large multispecialty clinic spent on their EHR in two types of visits – telemedicine and standard, in-person visits. The goal was to identify whether offering telemedicine visits changed the amount of time spent on EHR documentation.

The authors found that on days with telemedicine visits, clinicians spent an average of 14.8 minutes more on documentation in the EHR compared to days with no telemedicine visits. However, on days with only telemedicine visits, there was no increase in time spent in the EHR. This suggests that mixing in-person and telemedicine visits in the clinic may lead to inefficiencies as opposed to dedicating certain days to telemedicine visits. This suggests that a hybrid approach has drawbacks. If clinicians dedicate time to telemedicine, they may see improved outcomes.

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/mnOkFn7BNr9uoJMTCrVf.2","tags":[]}

# Conclusion

*Finish your paper with a summary of your work, major conclusions from your results, and potential recommendations for the future.*

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Nisl nunc mi ipsum faucibus vitae aliquet nec. Ornare massa eget egestas purus viverra accumsan in nisl. Orci dapibus ultrices in iaculis nunc sed augue lacus. Nec tincidunt praesent semper feugiat nibh sed pulvinar.

Odio aenean sed adipiscing diam donec. Risus viverra adipiscing at in tellus integer feugiat scelerisque. Pellentesque eu tincidunt tortor aliquam nulla facilisi cras fermentum odio. Urna porttitor rhoncus dolor purus non. Fringilla ut morbi tincidunt augue interdum. Viverra mauris in aliquam sem fringilla ut. Turpis egestas integer eget aliquet. Integer eget aliquet nibh praesent tristique magna.

+++ {"oxa":"oxa:tgSYYIag2qhHH1yPOHt4/6LM1hpBexLWItl5LHmo9.2","tags":[],"part":"acknowledgments"}

## Acknowledgements

*The acknowledgements section should include those who have aided in your work, provided data, tools, and/or funding. This section is typically not numbered with the rest of the paper. Section numbering is toggled on and off by highlight the heading and clicking the boxed number.*

