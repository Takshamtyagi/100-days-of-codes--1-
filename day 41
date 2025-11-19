#include <stdio.h>

int main() {
    int m, n;
    scanf("%d %d", &m, &n);
    int a[m][n];

    // Input matrix
    for (int i = 0; i < m; i++)
        for (int j = 0; j < n; j++)
            scanf("%d", &a[i][j]);

    // Print diagonal traversal
    for (int col = 0; col < n; col++) {
        int i = 0, j = col;
        while (i < m && j >= 0)
            printf("%d ", a[i++][j--]);
    }
    for (int row = 1; row < m; row++) {
        int i = row, j = n - 1;
        while (i < m && j >= 0)
            printf("%d ", a[i++][j--]);
    }
    return 0;
}
