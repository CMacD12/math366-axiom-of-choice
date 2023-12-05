Proof
=====

The axiom of choice seems to be obvious and intuitive, and in our everyday life there is no direct need to use since we are only concerned with finite sets. However, when we start to deal with infinite sets, we find that the axiom of choice is necessary to prove many theorems. In fact, it is so useful that it is often used without mention in many proofs.

Getting into the formality of mathematical logic for just a minute, the statement that a set :math:`B` is non-empty amounts to the first-order formula :math:`\phi(B):=(\exists x)(x\in B)` being true. If a set is known to be non-empty, we can infer that there is something in it, give it a name, and work with it. This rule of inference an example of *existential instantiation*.

Now in mathematical logic, we can “conjoin” finitely many formulas with “and” symbols. That is, if :math:`B_1, \cdots, B_n` are sets and we know each of them is non-empty, the following is also a formula of first-order logic.

.. math:: \phi(B_1)\wedge \cdots \wedge \phi(B_n)

(The symbol :math:`\wedge` means “and”) This allows us to find an element of each one, by instantiating a n-tuple of elements of the respective sets. We cannot, however, conjoin infinitely many statements. The system of logic in which mathematics is defined does not allow for infinite conjunctions. Roughly speaking, this is why we cannot simply produce an element from each set in an infinite collection of non-empty sets in general, but we can do it for any finite collection of sets.

Proofs that make no use of the Axiom of Choice are usually very constructive, in the sense that if they prove some object exists they tend to explicitly construct it. Proofs that do use Axiom of Choice often involve steps where we just ask Axiom of Choice to give us elements of sets, and then we work with them even though we know nothing else about them.

.. note:: **Fun Fact:** The axiom of choice is independent of the other axioms of set theory. This means that it is possible to construct a model of set theory in which the axiom of choice is true, and another model in which it is false. This is not the case for the other axioms of set theory, which are either true in all models or false in all models.

The Axiom of Choice needs to be an axiom simply because it cannot be proved from the other axioms. In fact, we have proved that we cannot prove it from the other axioms
