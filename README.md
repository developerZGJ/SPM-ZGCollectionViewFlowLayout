# ZGCollectionViewFlowLayout

一个可调整UICollectionView的cell布局方式Layout，可实现居中、居左、居右或自定义位置

# 安装

通过 Swift Package Manager安装

# 使用方法
```swift
        let layout = ZGCollectionViewFlowLayout()
        layout.cellType = .right
        let collectionView = UICollectionView(frame: .zero, collectionViewLayout: layout)
```
