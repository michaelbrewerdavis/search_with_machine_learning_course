
## Intermediate results

Results from running `./ltr-end-to-end.sh -m 0 -c quantiles`

### With name match

```
Simple MRR is 0.284
LTR Simple MRR is 0.149
Hand tuned MRR is 0.423
LTR Hand Tuned MRR is 0.160

Simple p@10 is 0.119
LTR simple p@10 is 0.074
Hand tuned p@10 is 0.171
LTR hand tuned p@10 is 0.077
Simple better: 670      LTR_Simple Better: 430  Equal: 15
HT better: 700  LTR_HT Better: 580      Equal: 10
```

### With name_phrase_match (slop=6)

```
Simple MRR is 0.284
LTR Simple MRR is 0.172
Hand tuned MRR is 0.423
LTR Hand Tuned MRR is 0.180

Simple p@10 is 0.119
LTR simple p@10 is 0.072
Hand tuned p@10 is 0.171
LTR hand tuned p@10 is 0.091
Simple better: 643      LTR_Simple Better: 454  Equal: 18
HT better: 688  LTR_HT Better: 593      Equal: 9
```

### with customer_review_average and customer_review_count

```
Simple MRR is 0.284
LTR Simple MRR is 0.393
Hand tuned MRR is 0.423
LTR Hand Tuned MRR is 0.386

Simple p@10 is 0.119
LTR simple p@10 is 0.154
Hand tuned p@10 is 0.171
LTR hand tuned p@10 is 0.160
Simple better: 507      LTR_Simple Better: 601  Equal: 7
HT better: 649  LTR_HT Better: 629      Equal: 12
```

### with artist_name, short_description, long_description phrase matches

```
Simple MRR is 0.284
LTR Simple MRR is 0.405
Hand tuned MRR is 0.423
LTR Hand Tuned MRR is 0.409

Simple p@10 is 0.119
LTR simple p@10 is 0.166
Hand tuned p@10 is 0.171
LTR hand tuned p@10 is 0.185
Simple better: 468      LTR_Simple Better: 634  Equal: 13
HT better: 579  LTR_HT Better: 688      Equal: 23
```

### with sales rank 

```
Simple MRR is 0.284
LTR Simple MRR is 0.440
Hand tuned MRR is 0.423
LTR Hand Tuned MRR is 0.449

Simple p@10 is 0.119
LTR simple p@10 is 0.172
Hand tuned p@10 is 0.171
LTR hand tuned p@10 is 0.185
Simple better: 459      LTR_Simple Better: 644  Equal: 12
HT better: 576  LTR_HT Better: 690      Equal: 24
```

### sku match, features match, in store availability

```
Simple MRR is 0.284
LTR Simple MRR is 0.435
Hand tuned MRR is 0.423
LTR Hand Tuned MRR is 0.423

Simple p@10 is 0.119
LTR simple p@10 is 0.172
Hand tuned p@10 is 0.171
LTR hand tuned p@10 is 0.182
Simple better: 456      LTR_Simple Better: 645  Equal: 14
HT better: 567  LTR_HT Better: 703      Equal: 20
```

### online availability, on sale, digital

```
Simple MRR is 0.284
LTR Simple MRR is 0.472
Hand tuned MRR is 0.423
LTR Hand Tuned MRR is 0.455

Simple p@10 is 0.119
LTR simple p@10 is 0.171
Hand tuned p@10 is 0.171
LTR hand tuned p@10 is 0.181
Simple better: 496      LTR_Simple Better: 612  Equal: 7
HT better: 587  LTR_HT Better: 680      Equal: 23
```

