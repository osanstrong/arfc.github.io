---
layout: manual
title: Masters Thesis
subtitle: "The difference between screwing around and science is writing it down. -- Adam Savage"
permalink: /manual/guides/writing/ms-thesis
---

## Before Writing

- Discuss your MS topic with your advisor. 
- Iterate on the topic until your advisor approves of the topic, scope, and 
  plan.
- Identify review and submission deadlines with your advisor.
- In collaboration with your advisor, identify a second reader.
- Send a polite email to the second reader asking if they would be willing and 
  proposing a review timeline.
- Create a GitHub repository where you will keep your thesis document.
- A UIUC MS thesis LaTeX template can be found at: 
  [https://github.com/arfc/ms-thesis-template](https://github.com/arfc/ms-thesis-template)
- Create a Zotero folder in paper-dev to hold your references 
  (YYYY-lastname-ms).
- Review the [graduate college format guidelines](http://www.grad.illinois.edu/thesis/thesishandbook/chapterIII.asp)

## Rules of the MS Thesis

There are many rules. From the grad handbook:

> The thesis should be a creative work of potential use to the nuclear, plasma,
> and radiological engineering community. The scope should permit completion
> within a reasonable time frame. The thesis must be deposited with the Graduate
> College Thesis Office. Publication is encouraged.  

## Review Process
The review process includes a series of major approvals:

1. Basic grammatical review & approval (e.g. by undergrad)
2. Approval by your advisor
3. Approval by the second reader
4. Approval by the department head
6. Approval by the graduate college

### Review Deadlines
It is best to work backward from the final deadline aiming to give at least two 
weeks to your second reader and to the department head.

| Stage                               | Days Before Deposit      | Duration            |
| :---------------------------------- | ------------------------ | ------------------: |
| Iterative Edits with Huff           | varies                   | varies |
| Submit final full draft to Huff     | 56                       | 2 weeks |
| Handle Final Huff Comments          | 42                  | 4 days |
| Submit to 2nd Reader                | 38                  | 2 weeks |
| Handle 2nd Reader Comments          | 24                  | 4 days  |
| Submit to Department Head           | 20                  | 2 weeks |
| Final Edits                         | 6                   | 2 days  |
| Graduate College Review             | 2                   | 2 days  |
| Deposit Deadline                    | 0                   | 0       |


#### Fall Example

An ideal fall, with a deposit deadline of December 11 might (ideally) look like this.


| Stage                           | Start Date  | End Date  |
| :------------------------------ | ----------: | --------: |
| Iterative Edits with Huff       | 09/15       | 10/16     |
| Submit final full draft to Huff | 10/16       | 10/30     |
| Handle Final Huff Comments      | 10/30       | 11/03     |
| Submit to 2nd Reader            | 11/03       | 11/17     |
| Handle 2nd Reader Comments      | 11/17       | 11/21     |
| Submit to Department Head       | 11/21       | 12/05     |
| Final Edits                     | 12/05       | 12/09     |
| Graduate College Review         | 12/09       | 12/11     |
| Deposit Deadline                | 12/11       | 12/11     |

#### Spring Example

An ideal spring, with a deposit deadline of April 26 might (ideally) look like this.


| Stage                           | Start Date    | End Date   |
| :------------------------------ | ------------: | ---------: |
| Iterative Edits with Huff       | varies        | varies     |
| Submit final full draft to Huff | 2/28          | 2 weeks    |
| Handle Final Huff Comments      | 3/03          | 4 days     |
| Submit to 2nd Reader            | 3/17          | 2 weeks    |
| Handle 2nd Reader Comments      | 3/31          | 4 days     |
| Submit to Department Head       | 4/04          | 2 weeks    |
| Final Edits                     | 4/20          | 2 days     |
| Graduate College Review         | 4/24          | 2 days     |
| Deposit Deadline                | 4/26          | 4/26       |


### Writing and Advisor Review 

The process can be either whole or piecemeal.
In Prof. Huff's experience, it is best to enable chapter-by-chapter review of your thesis by your advisor.
A great way to do this with Prof. Huff is the following workflow:

- Create a GitHub respository in your own GitHub user space.
- Work on this document in your repository. Feel free to use feature branches 
  and merge into master, or just commit directly to master as you go.
- At some point, you decide that a part of your masters thesis is ready for 
  Prof. Huff's review (e.g. the literature review chapter) 
- You need to give Prof. Huff collaborator permission on this repository to allow issue assignment.
- Tag the repository at that state. (e.g. ch1-draft-1)
- Create an issue like "Review Chapter 1" and assign Prof. Huff to that issue. 
  Note the repository tag in the issue description and *include a built `pdf` in 
  the issue.* 
- Prof. Huff will, within a week or two, conduct a review on the `pdf`.
- When Prof. Huff has completed the review, she will close the issue you 
  assigned to her and will open one or more NEW issues, assigned to you, 
  detailing the changes which must be made.
- Respond to the review issues via discussion on the github issue and ideally 
  with a PR. Prof. Huff can review your solutions to those issues by reviewing 
  pull requests, and/or by evaluating your progress in later stages of review.

When Prof. Huff approves, share the thesis with your second reader.

### Review by the second reader
Both the thesis advisor and the second reader should be given a month with the document.

## After Writing

- Add yourself to the degree list.
- File your thesis with the graduate school. 
- Complete any other degree-related beurocracy. 
- Add the thesis to ideals.
