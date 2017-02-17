# 用來發問及記錄問題的Respository
利用github的issue機制來做自己的問題庫

----
## 步驟教學

1. 建立issue
2. 若有解法則回覆comment
3. 關閉issue

----
## 問題範例

```markdown
這是問題摘要，請在此簡述問題
1. 最好是條列式
2. 最好是條列式
3. 最好是條列式

### 舉例
```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="horizontal" android:layout_width="match_parent"
    android:layout_height="match_parent">

    <ImageView
        android:layout_width="150dp"
        android:layout_height="150dp"
        android:id="@+id/imageView"
        android:scaleType="fitXY"
        android:background="@drawable/hyclogo"
        android:layout_centerInParent="true"/>
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/app_name"
        android:textSize="30sp"
        android:id="@+id/textView2"
        android:layout_below="@+id/imageView"
        android:layout_centerHorizontal="true" />

</RelativeLayout>```
```

## 解法紀錄範例
```markdown
這是解法摘要，請在此簡述問題
1. 最好是條列式
2. 最好是條列式
3. 最好是條列式

### 舉例
```xml
<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="30sp"
        android:id="@+id/textView2"
        android:layout_centerHorizontal="true" />```
```
