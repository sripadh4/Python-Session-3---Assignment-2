# Python-Session-3---Assignment-2
Print the required list comprehensions

List1 = ("Acadgild")
Solution = List1.upper()
Solution = list(Solution)
print (Solution)

Solution1 = [a*n for a in ["x", "y", "z"] for n in range(1, 5)]
print (Solution1)

Solution2a = [a for a in ["x", "y", "z"]]
Solution2b = [b*2 for b in ["x", "y", "z"]]*2
Solution2c = [c*4 for c in ["x", "y", "z"]]
print (Solution2a + Solution2b + Solution2c)

Solution3a = [[a] for a in range(2, 5)]
Solution3b = [[b] for b in range(3, 6)]
Solution3c = [[c] for c in range(4, 7)]
print (Solution3a + Solution3b + Solution3c)

Solution4a = [a for a in range(2, 6)]
Solution4b = [b for b in range(3, 7)]
Solution4c = [c for c in range(4, 8)]
Solution4d = [d for d in range(5, 9)]
print ([Solution4a] + [Solution4b] + [Solution4c] + [Solution4d])

Solution5a = [(b, a) for a in range(1, 4) for b in range(1, 4)]
print (Solution5a)
