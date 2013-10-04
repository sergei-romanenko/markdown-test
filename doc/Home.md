# Home

* [Page1](Page1.md)
* [Page1](Page2.md)

Line 1.
Line 2.
Line 3.

```
!#agda
ω =#? n = yes ω=j
# i =#? j with i N.≟ j
... | yes i≡j rewrite i≡j = yes #i=i
... | no  i≢j = no helper
  where helper : # i =# j → ⊥
        helper #i=j = i≢j (#i=#j→i≡j #i=j)
```

