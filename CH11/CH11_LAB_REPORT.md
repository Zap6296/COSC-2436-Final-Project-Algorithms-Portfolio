# Chapter 11: Dynamic Programming — Lab Report

## Student Information
- **Name:** Nathaniel Tryon
- **Date:** 4/26/26
- **Course:** COSC 2436

## Algorithm Summary
- **How it works:** dividing big problems into smaller problems to find the optimal solution so certain problems overlap subproblems and solves them in a bottom-up manner, storing and reusing solutions to avoid redundant computations.
- **Time complexity:** O(2n)
- **When to use it:** This is best used for when a problem can be broken into subproblems, and they don’t depend on each other.

## Test Results

                       1
                       1           2
                       1           2           3
                       1           2           3           4
                       1           2           3           4           5
                       1           2           3           4           5           6
- |GUITAR | $1500(G) | $1500(G) | $1500(G) | $1500(G) | $1500(G) | $1500(G)|
- |STEREO | $1500(G) | $1500(G) | $1500(G) | $3000(S) | $4500(GS) | $4500(GS)|
- |LAPTOP | $1500(G) | $1500(G) | $2000(L) | $3500(GL) | $4500(GS) | $4500(GS) |
- |iPHONE | $2000(i) | $3500(Gi) | $3500(Gi) | $4000(Li) |$5500(GLi) |$6500(GSi)|
- |BOOK | $2000(i) | $3500(Gi) | $3500(Gi) | $4000(Li) |$5500(GLi)| $6500(GSi)|
- |GOLD BAR| $30000(G) | $32000(iG)|$33500(GiG)|$33500(GiG)|$34000(LiG)|$35500(GLiG)|
