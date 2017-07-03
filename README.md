# CollapsingTabLayout

sample use of android material layout

CollapsingToolbarLayout and SwipeRefreshLayout

refer [SecondActivity](https://github.com/dotfeng/Dagger2MvpSample/blob/master/app/src/main/java/net/fengg/dagger2mvpsample/ui/view/activity/SecondActivity.java)/[activity_second.xml](https://github.com/dotfeng/Dagger2MvpSample/blob/master/app/src/main/res/layout/activity_second.xml) 


```
<CoordinatorLayout>
    <AppBarLayout>
        <CollapsingToolbarLayout>
            <ImageView/>
            <Toolbar>
                <TextView/>
            </Toolbar>
        </CollapsingToolbarLayout>
    </AppBarLayout>
    <SwipeRefreshLayout>
        <RecyclerView/>
    </SwipeRefreshLayout>
</CoordinatorLayout>

```

CollapsingToolbarLayout and TabLayout

[FourthActivity](https://github.com/dotfeng/Dagger2MvpSample/blob/master/app/src/main/java/net/fengg/dagger2mvpsample/ui/view/activity/FourthActivity.java)/[activity_fourth.xml](https://github.com/dotfeng/Dagger2MvpSample/blob/master/app/src/main/res/layout/activity_fourth.xml)

```
<CoordinatorLayout>
    <AppBarLayout>
        <CollapsingToolbarLayout>
            <ImageView/>
            <Toolbar>
                <TextView/>
            </Toolbar>
            <TabLayout/>
        </CollapsingToolbarLayout>
    </AppBarLayout>
    <ViewPager/>
</CoordinatorLayout>

```

