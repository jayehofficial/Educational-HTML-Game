KALEIDOSCOPE — Debugging Assessment: Answer Key

Q1: B   (arr[arr.length] is one past the last index -> undefined; off-by-one)
Q2: B   (i <= length reads nums[3] = undefined; sum + undefined = NaN)
Q3: C   (length is a property, not a method; calling it throws TypeError)
Q4: B   (the { } arrow body has no return, so map yields all undefined)
Q5: B   (= assigns "guest" (truthy) instead of comparing, so the if is always taken)
Q6: D   (null == 0 is false; null only loosely equals null/undefined. The other three are true)
Q7: B   (x === NaN is always false since NaN equals nothing; Number.isNaN(x) is true)
Q8: C   (user is undefined, so user.name throws a TypeError)
Q9: B   (var is function-scoped; all closures share one i, which ends at 3)
Q10: B  (sort() mutates in place AND returns the same array, so scores === top is true and both are sorted)
