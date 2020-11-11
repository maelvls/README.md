# Resume – Maël Valais, Software Engineer

Hi! My name is Maël from France. I am currently looking for a remote position as a Software Engineer.

I have been told I bring a cheerful presence to my colleagues through passion and honesty. I love the technical challenge of building an infrastructure product and always find ways of making my team happier by building cool CLIs or debugging some nasty Kubernetes networking issues.

You may read about me digging into networking, Go development, and Kubernetes in my [blog](https://maelvls.dev/).

Some of my contributions: [ocaml-minisat][], [ocaml-qbf][], [ocamlyices2][], [opam][] (OCaml), [gitlab-ce][] 
(Ruby), [boost-graph][] (C++), [auto-multiple-choice][] (C++, Perl), [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind/pulls?q=author%3Amaelvls) and [kubernetes-sigs/cluster-api](https://github.com/kubernetes-sigs/cluster-api/pulls?q=author%3Amaelvls+) (Go). I authored [homebrew-amc][], [touist][] (OCaml) and a couple of [vscode-extensions][].


[ocamlyices2]: https://github.com/polazarus/ocamlyices2/pulls?utf8=%E2%9C%93&q=author%3Amaelvls+
[ocaml-minisat]: https://github.com/c-cube/ocaml-minisat/pulls?utf8=%E2%9C%93&q=author%3Amaelvls
[ocaml-qbf]: https://github.com/c-cube/ocaml-qbf/issues?utf8=%E2%9C%93&q=author%3Amaelvls
[opam]: https://github.com/ocaml/opam-repository/pulls?utf8=%E2%9C%93&q=author%3Amaelvls
[gitlab-ce]: https://gitlab.com/gitlab-org/gitlab-ce/merge_requests/1150
[boost-graph]: https://github.com/boostorg/graph/issues?utf8=%E2%9C%93&q=author%3Amaelvls
[homebrew-amc]: https://github.com/maelvls/homebrew-amc
[auto-multiple-choice]: https://gitlab.com/jojo_boulix/auto-multiple-choice/-/commits/master?author=Ma%C3%ABl%20Valais
[touist]: https://github.com/touist/touist
[maelvls/awx-gke-terraform]: https://github.com/maelvls/awx-gke-terraform
[maelvls/terraform-touist]: https://github.com/maelvls/terraform-touist
[masters-thesis]: https://drive.google.com/file/d/0B5mz8k-t6PT0N2lINEZYX2duOFU/view
[vehicule-routing-report]: http://homepages.laas.fr/sungueve/Docs/Etu/rapport-ter-aide-humanitaire.pdf
[homebrew-tap-auto-bottles]: https://gist.github.com/maelvls/068af21911c7debc4655cdaa41bbf092
[maelvls/users-grpc]: https://github.com/maelvls/users-grpc
[rust-chat]: https://github.com/maelvls/rust-chat
[touist-server]: https://github.com/maelvls/touist-editor/blob/master/touist-server/src/main.rs
[maelvls.github.io]: https://maelvls.github.io/
[mael.valais@gmail.com]: mailto:mael.valais@gmail.com
[vscode-extensions-github]: https://github.com/maelvls?utf8=%E2%9C%93&tab=repositories&q=vscode&type=&language=
[vscode-extensions]: https://marketplace.visualstudio.com/search?term=maelvalais&target=VSCode&category=All%20categories&sortBy=Relevance
[linus-fuck-kay]: http://lkml.iu.edu/hypermail/linux/kernel/1404.0/01331.html


### System Software Engineer at Ori Industries _(2019–2020)_

As a Software Engineer at Ori Industries, my main focus was to develop an edge-aware version of Cloud Foundry. Telcos would use this infrastructure platform to leverage its low-latency last-mile 5G network. With this platform, they can sell compute time to developers with a network latency of 1-2 ms, acting as a public cloud provider of their own.

  

As an individual contributor, I helped shape the Kubernetes components that would make up the Ori infrastructure platform. Among others, my team built a Kubernetes native API for spinning up VMs on AWS, GCP, and OpenStack and bootstrap them into Kubernetes clusters. I also worked on a custom control plane for Envoy (our platform’s data plane) inspired by Istio. I contributed to the company’s initial REST API built-in Go that used a CQRS approach and NATS for the event persistence. My main achievement as an individual contributor has been to become the go-to person anyone would come to regarding Kubernetes controllers as well as for debugging Kubernetes and network-related issues.

  

After a few months, I stepped up as tech lead in a team of four people. I would run the daily standups, make sure the backlog is in good shape, work with the Product Manager to flesh out stories, point the stories with the team, run a biweekly retro meeting (we ended up working in an uninterrupted sprint). Notable achievements are the “project office hours” I started; the meeting increased the cross-team communication through demos and open discussions about anything more or less related to my team’s project.

Beyond my primary assignment, I also worked with the rest of the company on topics such as

*   Helped grow the remote-first culture thought experiments such as the “wormhole” and by pushing for better video call quality (more than 70% of the company now equipped with proper standalone mics such as the Blue Yeti). A blog post about my experience of remote work is published [here](https://medium.com/@bryony.snelling_26575/mr-remote-working-2c953c121968).
*   I initiated a movement towards transparency across the company that led to a rewrite of the “values” page. We started recording meetings and creating, for each meeting, a shared document with an agenda and collaboratively-written minutes.
*   Contributed to the company knowledge base on various topics such as “the git guide,” “slack etiquette,” and “recording and sharing meetings.”
*   Attended all weekly meetings of [sig-cluster-lifecycle](https://docs.google.com/document/d/1fQNlqsDkvEggWFi51GVxOglL2P1Bvo2JhZlMhm2d-Co/edit#) to keep the company up to date with upstream developments as well as advocate for our solution; contributions: [kubernetes\-sigs/kind](https://github.com/kubernetes-sigs/kind/pulls?q=author%3Amaelvls), [kubernetes\-sigs/cluster-api](https://github.com/kubernetes-sigs/cluster-api/pulls?q=author%3Amaelvls+)
*   I helped develop a self-learning program where each engineer spends 20% of their time training on various topics. I authored a couple of [blog posts](https://maelvls.dev/) and proposed learning topics engineers would pick during their training (mainly around Kubernetes controllers, networking, and Linux-y things).
*   I authored the technical test given to applicants and was part of the technical interviews.
*   I wrote multiple internal kubectl plugins for interacting with our custom resources and a tool for monitoring and removing unused VMs on OpenStack, AWS, and GCP.
*   I authored [ngroker](https://github.com/maelvls/ngroker), a tool we used at Ori for running a shared ssh session without the hassle of exchanging ssh keys (using Github usernames).
*   I wrote an interactive [ChatOps bot](https://github.com/maelvls/gh-actions-chatops) using Github Actions for applying Terraform changes through PRs.

**Tools used**: Go, Kubernetes, Github Actions, Helm, Terraform, AWS, GCP, OpenStack, Agile.

### Fullstack Software Engineer contracted to La Banque Postale _(2019)_

As part of a network operations team, I built a web application meant to become a self-updating repository of IP assignments (as opposed to using Excel sheets), which helps the operations team plan and execute fail-overs.

**Tools used:** Java, Spring Boot, Typescript, Angular 2+, NgRx.

### Systems Software Engineer contracted to Orange _(2018)_

As part of an operations team, I built a Terraform plugin in Go for a private cloud used within Orange (mainly interacting with VMWare vRA 7 APIs). I also worked on the continuous testing and delivery of Docker images used by application teams across the company.

**Tools used:** Go, Terraform, Gitlab CI, Bash, VMWare vRA 7.

### Education

### Ph.D. in Computer Science _(2016–2018)_

I developed [touist](https://github.com/touist/touist), a compiler written in OCaml for a new logic language meant to formalize and solve problems expressed as SAT expressions. The tool is now used to teach logic to first-year students at Université Paul Sabatier in Toulouse and is used by researchers to explore new SAT encodings.

As part of my PhD, I also helped develop a web application serving as a frontend to the compiler written in VueJS and Rust; we deployed it through Docker images built by Travis CI and run using AWS ECS.

**Tools used:** OCaml, Rust, Typescript, AWS ECS, Travis CI.

## Contact details

- mael.valais@gmail.com
- +33 786484391
- _Maël Valais_ on [Kubernetes Slack](https://slack.k8s.io/) and [Gopher Slack](https://gophersinvite.herokuapp.com/)
- [LinkedIn](https://www.linkedin.com/in/maelvalais/)
- [Blog](https://maelvls.dev)
- Toulouse, France
