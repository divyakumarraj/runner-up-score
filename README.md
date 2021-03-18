# runner-up-score
The first line contains n The second line contains an array A of n integers each separated by a space.

if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())
    arr=sorted(arr,reverse=True)
    for i in range(len(arr)):
        if arr[i]==arr[0]:
            continue
        else:
            print(arr[i])  
            break
