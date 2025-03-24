#!/usr/bin/python3
'''Pascal’s triangle of n:'''


def pascal_triangle(n):
    '''returns the pascals triangle '''
    outer_list = []

    for i in range(n):
        if i == 0:
            outer_list.append([1])
        elif i == 1:
            outer_list.append([1, 1])
