## Construction BST of [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

The first element of this array is taken as starting root of a BST.

The root [7]. 
Comparison with next elements of this array will be [5] on left side of the root.

                                        [7]
                                    [5]

Now root still has the same value. The next element [1] will be on again left side of the root after series of comparisons.

                                        [7]
                                    [5]
                                [1]

For each element on this array, same procedure has applied and the final tree as seen in below;

                                        [7]
                                    [5]     [8]
                                [1]

                                        '
                                        '
                                        '
                                        '
                                        [7]
                             [5]                   [8]
                        [1]       [6]                  [9]
                    [0]     [3]
                         [2]   [4]