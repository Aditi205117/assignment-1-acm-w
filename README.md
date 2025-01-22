# assignment-1-acm-w
Q1
void setZeroes(int** matrix, int matrixSize, int* matrixColSize) {
    int r=matrixSize;
    int c= *matrixColSize;
    int i,j;
     int rflag;
      int cflag;
    for(i=0;i<r;i++){
        for(j=0;j<c;j++){
            if(matrix[i][j]==0){
                rflag=1;
                //cflag=1;
                }}}

    for (int i=0;i<r;i++){
        if ( cflag==1){
            for(int j=0;j<c;j++)
            matrix[i][j]=0;
        }
    }
     for (int j=0;j<r;j++){
        if (rflag==1){
            for(int i=0;i<c;i++)
            matrix[i][j]=0;
        }
    }
}
