Output for the above input 

put 2 9
print_stats_tree

2:9(1){1,9,9,9}
put 9 -2
print_stats_tree

        9:-2(1){1,-2,-2,-2}

2:9(2){2,7,-2,9}
put 3 5
print_stats_tree

        9:-2(1){1,-2,-2,-2}

3:5(2){3,12,-2,9}

        2:9(1){1,9,9,9}
put 1 2
print_stats_tree

        9:-2(1){1,-2,-2,-2}

3:5(3){4,14,-2,9}

        2:9(2){2,11,2,9}

                1:2(1){1,2,2,2}
put 2 10
print_stats_tree

        9:-2(1){1,-2,-2,-2}

3:5(3){4,15,-2,10}

        2:10(2){2,12,2,10}

                1:2(1){1,2,2,2}
put 7 -4
size
5
print_stats_tree

        9:-2(2){2,-6,-4,-2}

                7:-4(1){1,-4,-4,-4}

3:5(3){5,11,-4,10}

        2:10(2){2,12,2,10}

                1:2(1){1,2,2,2}
erase 3
print_stats_tree

        9:-2(1){1,-2,-2,-2}

7:-4(3){4,6,-4,10}

        2:10(2){2,12,2,10}

                1:2(1){1,2,2,2}
erase 7
print_stats_tree

        9:-2(1){1,-2,-2,-2}

2:10(2){3,10,-2,10}

        1:2(1){1,2,2,2}
size
3
put 3 1
print_stats_tree

        9:-2(2){2,-1,-2,1}

                3:1(1){1,1,1,1}

2:10(3){4,11,-2,10}

        1:2(1){1,2,2,2}
put 7 -10
size
5
print_stats_tree

                9:-2(1){1,-2,-2,-2}

        7:-10(2){3,-11,-10,1}

                3:1(1){1,1,1,1}

2:10(3){5,1,-10,10}

        1:2(1){1,2,2,2}
print
[2:10]([1:2](),()),([7:-10]([3:1](),()),([9:-2](),()))
print_key_stats 7
7:-10(2){3,-11,-10,1}
find 2
10
find 5
Not found!
print_key_stats 4
Not found!
print
[2:10]([1:2](),()),([7:-10]([3:1](),()),([9:-2](),()))
print_stats
[2:10(3){5,1,-10,10}]([1:2(1){1,2,2,2}](),()),([7:-10(2){3,-11,-10,1}]([3:1(1){1,1,1,1}](),()),([9:-2(1){1,-2,-2,-2}](),()))
print_tree

                9:-2

        7:-10

                3:1

2:10

        1:2


