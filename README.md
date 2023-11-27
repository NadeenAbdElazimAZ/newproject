# newproject

## add ttwo branches (dev = > (fiel 1 , fiel 2) , test) :

![Screenshot from 2023-11-27 23-45-03](https://github.com/NadeenAbdElazimAZ/newproject/assets/152066408/2836fff2-0be8-43c5-a6f7-14be5900b0c0)

## merge dev branch 

![WhatsApp Image 2023-11-27 at 11 34 57 PM](https://github.com/NadeenAbdElazimAZ/newproject/assets/152066408/4217064b-cab3-41a1-85eb-e4970507ed6d)

## to delete branch remotly
```
git push origin --delete dev
```
## to delete branch locally 
```
git branch -d dev
```

## tag 

![WhatsApp Image 2023-11-27 at 11 34 58 PM(1)](https://github.com/NadeenAbdElazimAZ/newproject/assets/152066408/b3e8fc22-8eaf-4f18-9fc8-54e07eb6c90b)

## to list tag locally 
```
git tag

```

## to delete tag locally 
```
git tag -d v1.4
```
## to delete tag remotly
```
git push origin --delete v1.4
```

## what the rebase 
 the process of moving or combining a sequence of commits to a new base commit. 
 
data:image/png;base64,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
