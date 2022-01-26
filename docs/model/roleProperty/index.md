---
title: "roleProperty"
---

> [Model](../../) > roleProperty

## Label

### English
roleProperty


## Definition
is defined by http://www.w3.org/ns/org This is a metalevel property which is used to annotate an `org:Role` instance with a sub­property of `org:memberOf` that can be used to directly indicate the role for easy of query. The intended semantics is a Membership relation involving the Role implies the existence of a direct property relationship through an inference rule of the form: `{ [] org:member ?p; org:organization ?o; org:role [org:roleProperty ?r] } ­> {?p ?r ?o}`. 


    
