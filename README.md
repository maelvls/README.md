# Resume – Maël Valais, Software Engineer

Hi! My name is Maël from France. I am currently looking for a remote position as a Software Engineer. In a few words, I have been told that I bring a cheerful presence to my colleagues though passion and honesty. I love the technical challenge of building an infrastructure product, and always find ways of making my team happier by building cool CLIs or debugging some nasty Kubernetes networking issue.

## System Software Engineer at Ori Industries _(2019–2020)_

As a Software Engineer at Ori Industries, my main focus was to develop an infrastructure platform that can be seen as an edge-aware version of Cloud Foundry that telcos would use to leverage their low-latency last-mile 5G network. With this platform, telcos are able to sell compute time to developers with a network latency of 1-2 ms, acting as a public cloud provider of their own.

In my capacity as an Individual Contributor, I helped shape the Kubernetes components that would make up the Ori infrastructure platform. Among others, my team built a Kubernetes native API for spinning up VMs on AWS, GCP and OpenStack and bootstrap them into Kubernetes clusters. I also worked on a custom control plane for Envoy (our platform's data plane) inspired by Istio; and contributed to the company's early REST API built in Go that used a CQRS approach and NATS for the event persistence. My main achivement as an Individual Contributor has been to become the go-to person anyone would come to regarding Kubernetes controllers as well as for debugging Kubernetes and network-related issues.

After a few months, I stepped up as Tech Lead in a team of four people. I would run the daily standups, make sure the backlog is in good shape, work with the Product Manager to flesh out stories, point the stories with the team, run a biweekly retro meeting (we ended up working in an uninterrupted sprint). Notable achivements are the "project office hours" I started; the meeting increased the cross-team communication through demos and open discussions about anything more or less related to my team's project.

Beyond my main assignment, I also worked with the rest of the company on topics such as

- Helped grow the remote-first culture thought experiments such as the "wormhole" and by pushing for better video call quality (more than 70% of the company now equipped with proper standalone mics such as the Blue Yeti). A blog post about my experience of remote work is published [here](https://medium.com/@bryony.snelling_26575/mr-remote-working-2c953c121968).
- Initiated a movement towards transparency across the company that led to a rewrite of the "values" page as well as many changes such as recording meetings and having a shared document with an agenda and minutes for every single meeting.
- Contributed to the company knowledge base on various topics such as "the git guide", "slack etiquette" and "recording and sharing meetings".
- Attended all weekly meetings of [sig-cluster-lifecycle](https://docs.google.com/document/d/1fQNlqsDkvEggWFi51GVxOglL2P1Bvo2JhZlMhm2d-Co/edit#) with the goal of keeping the company up to date with upstream developments as well as advocating for our solution; contributions: [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind/pulls?q=author%3Amaelvls), [kubernetes-sigs/cluster-api](https://github.com/kubernetes-sigs/cluster-api/pulls?q=author%3Amaelvls+)
- Helped develop a self-learning program where each engineer is given 20% of their time to train on various topics; I authored a couple of [blog posts](https://maelvls.dev/) as well as many ideas of topics engineers would pick during their training (mainly around Kubernetes controllers, networking and Linux-y things).
- Authored the technical test given to applicants and follow-up technical interviews.
- Authored multiple internal kubectl plugins for interacting with our custom resources as well as a tiny tool for monitoring and removing unused VMs on OpenStack, AWS and GCP.
- Authored [ngroker](https://github.com/maelvls/ngroker), a tool we used at Ori for running a shared ssh session without the hassle of exchanging ssh keys (using Github usernames).
- Wrote an interactive [ChatOps bot](https://github.com/maelvls/gh-actions-chatops) using Github Actions for applying Terraform changes through PRs.

**Tools used**: Go, Kubernetes, Github Actions, Helm, Terraform, AWS, GCP, OpenStack, Agile.

## Fullstack Software Engineer contracted to La Banque Postale _(2019)_

As part of a network operations team, I built a web application meant to become a self-updating repository of IP assignments (as opposed to using Excel sheets) and that helps the operations team plan and execute fail-overs.

**Tools used:** Java, Spring Boot, Typescript, Angular 2+, NgRx.

## Systems Software Engineer contracted to Orange _(2018)_

As part of an operations team, I worked on building a Terraform plugin in Go for a private cloud used within Orange (mainly interacting with VMWare vRA 7 APIs). I also worked on the continous testing and delivery of Docker images used by application teams across the company.

**Tools used:** Go, Terraform, Gitlab CI, Bash, VMWare vRA 7.

## Education

### PhD in Computer Science _(2016–2018)_

I developed [touist](https://github.com/touist/touist), a compiler written in OCaml for a new logic language meant to formalize and solve problems that can be expressed as SAT expressions. The tool is now used to teach logic to first-year students at Université Paul Sabatier in Toulouse and is used by reseachers to explore new SAT encodings.

As part of my PhD, I also helped develop a web application serving as a frontend to the compiler written in VueJS and Rust; we deployed it through Docker images built by Travis CI and run using AWS ECS.

**Tools used:** OCaml, Rust, Typescript, AWS ECS, Travis CI.

## Contact details

- mael.valais@gmail.com
- +33 786484391
- _Maël Valais_ on [Kubernetes Slack](https://slack.k8s.io/) and [Gopher Slack](https://gophersinvite.herokuapp.com/)
- [LinkedIn](https://www.linkedin.com/in/maelvalais/)
- [Blog](https://maelvls.dev)
- Toulouse, France
