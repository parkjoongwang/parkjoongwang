#include <stdio.h>
#include <stdbool.h>
#include <stdlib.h>

int solution(int ang) {
    int ans = 1;    
    return ang<90?1:ang==90?2:ang<180?3:4;
}
