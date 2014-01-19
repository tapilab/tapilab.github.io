---
layout: post
category : Information Extraction
title: Extracting social networks and contact information from email and the Web
venue: CEAS 2004
authors: Aron Culotta, Ron Bekkerman, and Andrew McCallum
key: culotta04extracting
tags: [CRFs]
---

{% include JB/setup %}


#### Abstract

We present an end-to-end system that extracts a user's social network and its
members' contact information given the user's email inbox. The system
identifies unique people in email, finds their Web presence, and automatically
fills the fields of a contact address book using conditional random fields---a
type of probabilistic model well-suited for such information extraction
tasks. By recursively calling itself on new people discovered on the Web, the
system builds a social network with multiple degrees of separation from the
user. Additionally, a set of expertise-describing keywords are extracted and
associated with each person. We outline the collection of statistical and
learning components that enable this system, and present experimental results
on the real email of two users; we also present results with a simple method
of learning transfer, and discuss the capabilities of the system for
address-book population, expert-finding, and social network analysis.

#### Citation

	@inproceedings{culotta04extracting,
	  author = {Aron Culotta and Ron Bekkerman and Andrew McCallum},
	  title = {Extracting social networks and contact information from email and the Web},
	  booktitle = {First Conference on Email and Anti-Spam (CEAS)},
	  address = {Mountain View, CA},
	  year = {2004},
	}
