# Learn to Build Kubernetes Operators

> Collection of learning material for building Kubernetes Operators.
> As a big fan of automating everything in Kubernetes, Operator pattern got my interests quickly.
> However, it took me a while to figure out the technical know-how of building an Operator.
> I hope that this learning journey from my learning experience will help the builder get started faster.

## The Journey

- [Why Operators and What is it?](#why-operators-and-what-is-it)
- [The foundations](#the-foundations)
  - [Kubernetes](#kubernetes)
  - [GoLang](#golang)
  - [Custom Resource Definition (CRD)](#crd)
- [Hello Operators](#hello-operators)
- [For the Operator Builders](#for-the-operator-builders)
- [The Operator Ecosystem](#the-operator-ecosystem)
- [How to participate and contribute](#how-to-participate-and-contribute)

## Why Operators and What is it?

Always ask the why question before learning anything. Here is my thoughts:

- Community is looking for a consistent way to release and operate software on Kubernetes
- Stateful application is hard
- Demand for Operation-As-code in Kubernetes

What is Operator: 
- Approach to automate applications in Kubernetes, specifically for distributed Stateful application.

Blogs and videos:
- [Why Kubernetes Operators are a game changer](https://blog.couchbase.com/kubernetes-operators-game-changer/)
- [How to explain Kubernetes Operators in plain English](https://enterprisersproject.com/article/2019/2/kubernetes-operators-plain-english?sc_cid=7016000000127eyAAA)
- [(An Attempt at) Learning Kubernetes Operators for StatefulSet Recovery](https://medium.com/@joatmon08/an-attempt-at-learning-kubernetes-operators-dace89e573b1)
- [(Video) Lightning Talk: Why You Care About Kubernetes Operators - Josh Wood, Red Hat](https://www.youtube.com/watch?v=6Csf0g9BTr4)
- [What not to talk about when talking Operators (in Chinese, need translation)](https://www.infoq.cn/article/SJMUvMg_0H7BS5d99euR)
- [Brandon Philips gist of Third Party Resource (TPR)](a97a143546c87b86b870a82a753db14c) - A little history of emergence of Operators
