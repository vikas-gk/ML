<h2>General Boundary</h2>

The general boundary G, with respect to hypothesis space H and training
data D, is the set of maximally general members of H consistent with D.


<h2>Specific Boundary</h2>
The specific boundary S, with respect to hypothesis space H and training
data D, is the set of minimally general (i.e., maximally specific) members of H
consistent with D.
  
  As long as the sets G and S are well defined, they completely
specify the version space. In particular, we can show that the version space
is precisely the set of hypotheses contained in G, plus those contained in S, plus
those that lie between G and S in the partially ordered hypothesis space.

<h2>Version Space Representation Theorem</h2>
  Let X be an arbitrary set of instances and let H be a set of boolean-valued hypotheses defined over X. Let
c : X -> {O, 1) be an arbitrary target concept defined over X, and let D be an
arbitrary set of training examples {(x, c(x))). For all X, H, c, and D such that S and
G are well defined,
