# CSIS Government Open Source Software Policies Dataset

This dataset captures the different ways in which governments around the world have engaged
with open source software (OSS).

This dataset was prepared by Eugenia Lostri, Georgia Wood, and Megha Jain from the Center for Strategic and International Studies (CSIS).

You can explore summary visualizations of the dataset [here](#placeholder-pages-deploy-link) or perform your own analyses by creating a [Codespace](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=github/government-open-source-policies). The raw dataset is available [here](https://github.com/github/government-open-source-policies/blob/main/data/OSS.Dataset.-.December.2022.v3.csv). The dataset can also be accessed on the [CSIS website](https://www.csis.org/programs/strategic-technologies-program/government-open-source-software-policies).

Comments, corrections and new data are welcome. Please review our [Contribution page](./CONTRIBUTING.md).

## Description

The research team relied on publicly available information to
populate the dataset. To capture a broad array of policies, we used unofficial translations. The
research took place between January - August 2022; however, we have included some well-
documented policies and bills that have been introduced since then.

This dataset builds on previous CSIS surveys on OSS policies (the 2010 update can be accessed
here). However, given the developments in the last decade, we found it necessary to adapt the
dataset to better fit the type of policies we found in this iteration. For starters, and as a matter of
scope, this dataset focuses on those initiatives introduced at the national level. In past iterations
we included local and regional initiatives, since a lot of the drive for OSS was occurring at those
levels. Since then, national governments have increased their interest in OSS policies – we found
a total of 669 policies. After identifying them, we examined them and categorized them
according to the following criteria:

1. Title: When a title was not available, we included a short description of the action in the
   title cell. Thus, some titles are not official.
2. Issuing Authority: identifies which elements of the national government are working on
   OSS. We have divided this into five categories: 1. Agency 2. Armed Forces 3. Executive 4. Legislative 5. Ministry
3. Type of Policy/Document: 1. Bill: introduced bills or laws. 2. Others: miscellaneous documents that outline actions or understandings. For
   example, guidelines, studies, white papers. 3. Directives &amp; Regulation: regulatory documents not stemming from the legislative
   branch. For example, decrees, executive orders, directives or memoranda. 4. Support: documents that do not regulate OSS but convey the issuing authorities’
   position. For example, announcements, statements, programs, or meetings. 5. Strategy: action plans or strategies that chart a course and objective.
4. OSS Specific: identifies whether OSS is a standalone issue, or if it is a pillar or course of
   action in a broader initiative.
5. Stated Objective: examines the reasons governments use to justify the adoption of the
   policy. We used the following categories: 1. Cost: governments frequently cite the cost of proprietary software as a reason to
   study or promote the use of OSS. This category also includes those policies that
   recognized OSS as an alternative to the use of pirated software by government
   entities. 2. Sovereignty: some governments perceive OSS as a way to achieve tech
   sovereignty and autonomy, stopping them from being dependent on third-country
   technology. 3. Support for National Industry: some governments advocated for these initiatives
   as a way to support the development of a national software industry. 4. Modernization: some governments advocate for OSS as a tool to advance the
   modernization of government systems and society. This includes, for example,
   efforts at digitization, e-government, interoperability, trainings to increase
   awareness and capacity. 5. Transparency: some governments viewed OSS as a way to increase transparency
   on how funds are used by the government and how procurement is arranged. The
   use of OSS could also increase visibility into the systems themselves. 6. Security: some governments see OSS as a way to increase security of their
   systems. This category also includes those policies that address the security of the
   OSS solutions themselves.
6. Type of action: we have expanded the list of categories under which we classified the
   actions required by the policy to include: 1. Cooperation: public-private partnerships between government entities and the
   OSS community. 2. How to Use: guidelines or instructions for how to develop, implement, or
   transition to OSS solutions. 3. Procurement – advisory: the use of OSS should be considered. 4. Procurement – mandatory: the use of OSS is mandated, given preference over
   proprietary software, or is a prerequisite for selection of a project. 5. R&amp;D: studies, white papers, comments, or other initiatives on the viability or
   feasibility of OSS, and requirements for openness (open by default), which would
   benefit users and other governmental bodies. 6. Repository: development of a repository, not the repository itself. 7. Training: trainings on OSS development or use for citizens or civil servants. 8. Tech Neutrality: explicit endorsement of the principle of tech neutrality – the
   freedom to choose the technology that is most adequate to the needs.
7. Terms: identifies what terminology governments use, distinguishing between open source
   software (OSS), free (libre) open source software (FLOSS/FOSS), public software, or if
   they use some of these terms interchangeably. It is important to note in some cases we
   had to make a determination without having access to primary sources, or relying on
   unofficial translations.
8. Status: identifies whether a policy has been proposed, approved, replaced, or if it failed.
   When we found old announcements and no update, we noted the lack of update and kept
   the categorization as “approved.” When we found proposed legislation with no update and more than 2 years passed since it was introduced, we considered it “failed.” This
   category is mostly useful for legislative actions, since there is little visibility into
   proposed or failed ministerial or executive action.

## Footnotes

To provide clarification on certain policies, researchers included footnotes in the web version of
the dataset, and entries in the “notes” column in the csv file.

1. Details need to be confirmed. No access to original source, cannot locate it elsewhere. In
   places where the researchers felt it necessary, footnotes are included to flag there was limited
   access to data on a certain entry.
2. Proposed in cited year; no update found. If an entry was proposed, but no since update was
   found by researchers, this was often noted.
3. Unclear when it was established. When the source does not indicate with clarity when the
   action was created, announced, established, etc.
4. Link recently broke; not available in Wayback machine. When the link to the action’s source
   is no longer working, but was available during the time of data collection, researchers put this
   footnote on the entry.

## Tips for Using the Dataset

- On the web version, you can sort alphabetically by clicking the header of each column, or
  reverse alphabetically by clicking it again. There is also a sort function that allows you to
  browse for key words throughout the dataset. For example, if you would like to search for
  Argentina’s strategy on OSS, we recommend first sorting alphabetically, then type
  strategy into the search bar.
- For sorting by multiple columns, we recommend you download the CSV file.
- Some links will automatically download a file. Make sure your browser allows pop-ups.
- A note on Argentina’s legislation: links might not redirect to the bill, but to the
  parliamentary search function. You can access the bill by searching for the “name” on the
  “Nro. de Expediente” category.

## Acknowledgements

The researchers would like to thank Andrew Braverman and Elizabeth Benke for their research
support in the early stages of this project. They would also like to thank the welcoming members
of the OSS community who were generous with their time and insights, and helped shape this
dataset.
This work benefited extensively from the work done by the Wayback Machine. This dataset
would not be as complete without it.

This work was made possible through support from GitHub.
