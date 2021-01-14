---
layout: page
title: Examples of Topological Spaces
---

**Definition.** *A **topology** on a set $ X $ is a collection $ T $ of subsets of $ X $ s.t.*

1. $ \0, X \in T. $
2. The union of elements of any subcollection of $ T $ is in $ T. $
3. The intersection of elements of any finite subcollection of $ T $ is in $ T. $

Such a set $ X $ is called a ***topological space.*** A subset $ U \sub X $ is called ***open*** if $ U \in T. $ In other words, a topological space $ X $ is a set $ X $ endowed with a collection of open subsets, s.t. $ \0 $ and $ X $ are open, and the union of arbitrary open sets and the finite intersection of open sets are open.

**Example.** Let $ X $ be any set. Then the collection of all subsets of $ X $
is a topology, called the ***discrete topology.*** The ***indiscrete / trivial
topology*** is the collection consisting only of $ \0 $ and $ X $ itself.

**Example.** Let $ X $ be a set. The ***finite complement topology*** on $ X $
is the collection $ T_f $ of subsets $ U \sub X $ s.t. $ X - U $ is either
finite or all of $ X. $

**Example.** Similarly, let $ X $ be a set. The ***countable complement topology*** on $ X $ is the collection $ T_c $ of subsets $ U \sub X $ s.t. $ X - U $ is either countable or all of $ X. $

**Example.** Let $ X $ be a metric space with metric $ d, $ and let $ T $ be its open subsets given by $ d $. Then $ T $ is a topology, and we say it's ***induced by the metric*** $ d. $

**Definition.** *Let $ T, T' $ be two topologies for $ X. $ We say that $ T' $ is **finer** than $ T $ and $ T $ is **coarser** than $ T' $ if $ T \sub T' $. We say **strictly finer or coarser** if set equality does not hold. We say $ T $ and $ T' $ are **comparable** if either $ T $ is finer or coarser than $ T'. $*