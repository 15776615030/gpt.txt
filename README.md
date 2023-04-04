# classes2.dex

.class public final Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;
.super Lf/n/c/a/a;
.source "BookDivisionActivity.kt"

# interfaces
.implements Landroid/view/View$OnClickListener;


# annotations
.annotation system Ldalvik/annotation/MemberClasses;
    value = {
        Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;
    }
.end annotation

.annotation runtime Lf/n/c/t/j;
    value = {
        Lf/n/g/f/c/d/s;,
        Lf/n/g/f/c/d/n;
    }
.end annotation


# instance fields
.field public final A:Li/d;

.field public final r:Li/d;

.field public final s:Li/d;

.field public final t:Li/d;

.field public final u:Li/d;

.field public final v:Li/d;

.field public final w:Li/d;

.field public final x:Li/d;

.field public final y:Li/d;

.field public final z:Lf/n/g/f/c/f/c;


# direct methods
.method public constructor <init>()V
    .registers 4

    .line 1
    invoke-direct {p0}, Lf/n/c/a/a;-><init>()V

    .line 2
    sget v0, Lcom/junyue/novel/modules_index/R$id;->toolbar:I

    invoke-static {p0, v0}, Lf/l/a/a/a;->a(Landroid/app/Activity;I)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->r:Li/d;

    .line 3
    sget v0, Lcom/junyue/novel/modules_index/R$id;->bookshelf_div:I

    invoke-static {p0, v0}, Lf/l/a/a/a;->a(Landroid/app/Activity;I)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->s:Li/d;

    .line 4
    sget v0, Lcom/junyue/novel/modules_index/R$id;->menu_right:I

    invoke-static {p0, v0}, Lf/l/a/a/a;->a(Landroid/app/Activity;I)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->t:Li/d;

    .line 5
    sget v0, Lcom/junyue/novel/modules_index/R$id;->iv_more:I

    invoke-static {p0, v0}, Lf/l/a/a/a;->a(Landroid/app/Activity;I)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->u:Li/d;

    .line 6
    sget v0, Lcom/junyue/novel/modules_index/R$id;->tv_cancel:I

    invoke-static {p0, v0}, Lf/l/a/a/a;->a(Landroid/app/Activity;I)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->v:Li/d;

    .line 7
    sget v0, Lcom/junyue/novel/modules_index/R$id;->cv_bottom_nav:I

    invoke-static {p0, v0}, Lf/l/a/a/a;->a(Landroid/app/Activity;I)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->w:Li/d;

    .line 8
    new-instance v0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$e;

    invoke-direct {v0, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$e;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    invoke-static {v0}, Li/f;->b(Li/a0/c/a;)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->x:Li/d;

    .line 9
    new-instance v0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$f;

    invoke-direct {v0, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$f;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    invoke-static {v0}, Li/f;->b(Li/a0/c/a;)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->y:Li/d;

    .line 10
    new-instance v0, Lf/n/g/f/c/f/c;

    new-instance v1, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$b;

    invoke-direct {v1, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$b;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    .line 11
    new-instance v2, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$c;

    invoke-direct {v2, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$c;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    .line 12
    invoke-direct {v0, v1, v2}, Lf/n/g/f/c/f/c;-><init>(Li/a0/c/l;Li/a0/c/l;)V

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->z:Lf/n/g/f/c/f/c;

    .line 13
    new-instance v0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$d;

    invoke-direct {v0, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$d;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    invoke-static {v0}, Lf/n/c/c0/c1;->b(Li/a0/c/a;)Li/d;

    move-result-object v0

    iput-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->A:Li/d;

    return-void
.end method

.method public static final synthetic e1(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)Ljava/util/List;
    .registers 1

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->m1()Ljava/util/List;

    move-result-object p0

    return-object p0
.end method

.method public static final synthetic f1(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;
    .registers 1

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->o1()Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;

    move-result-object p0

    return-object p0
.end method

.method public static final synthetic g1(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)Ljava/util/ArrayList;
    .registers 1

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->q1()Ljava/util/ArrayList;

    move-result-object p0

    return-object p0
.end method

.method public static final synthetic h1(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)Lcom/junyue/novel/skin/skin2/widget/DefaultTitleBar;
    .registers 1

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->w1()Lcom/junyue/novel/skin/skin2/widget/DefaultTitleBar;

    move-result-object p0

    return-object p0
.end method

.method public static final synthetic i1(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;Ljava/lang/Object;)V
    .registers 2

    .line 1
    invoke-virtual {p0, p1}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->y1(Ljava/lang/Object;)V

    return-void
.end method

.method public static final synthetic j1(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V
    .registers 1

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->A1()V

    return-void
.end method

.method public static final synthetic k1(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;Z)V
    .registers 2

    .line 1
    invoke-virtual {p0, p1}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->B1(Z)V

    return-void
.end method


# virtual methods
.method public final A1()V
    .registers 9

    .line 1
    sget-object v5, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$l;->a:Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$l;

    .line 2
    new-instance v6, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$m;

    invoke-direct {v6, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$m;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    .line 3
    sget-object v7, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$n;->a:Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$n;

    const-string v1, ""

    const-string v2, ""

    const-string v3, "取消"

    const-string v4, "重命名"

    move-object v0, p0

    .line 4
    invoke-static/range {v0 .. v7}, Lf/n/g/f/c/f/g/c;->a(Landroid/app/Activity;Ljava/lang/String;Ljava/lang/String;Ljava/lang/String;Ljava/lang/String;Li/a0/c/a;Li/a0/c/a;Li/a0/c/a;)Lf/n/g/f/c/f/g/d;

    move-result-object v0

    .line 5
    invoke-virtual {v0}, Landroid/app/Dialog;->show()V

    return-void
.end method

.method public final B1(Z)V
    .registers 5

    const/4 v0, 0x0

    const/4 v1, 0x1

    if-eqz p1, :cond_21

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->s1()Landroid/view/View;

    move-result-object v2

    invoke-static {v2, v0}, Le/a/b/b;->a(Landroid/view/View;Z)V

    .line 2
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->r1()Landroid/view/View;

    move-result-object v0

    invoke-static {v0, v1}, Le/a/b/b;->a(Landroid/view/View;Z)V

    .line 3
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->p1()Landroidx/cardview/widget/CardView;

    move-result-object v0

    invoke-static {v0, v1}, Le/a/b/b;->a(Landroid/view/View;Z)V

    .line 4
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->o1()Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;

    move-result-object v0

    invoke-virtual {v0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;->k()V

    goto :goto_3d

    .line 5
    :cond_21
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->s1()Landroid/view/View;

    move-result-object v2

    invoke-static {v2, v1}, Le/a/b/b;->a(Landroid/view/View;Z)V

    .line 6
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->r1()Landroid/view/View;

    move-result-object v1

    invoke-static {v1, v0}, Le/a/b/b;->a(Landroid/view/View;Z)V

    .line 7
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->p1()Landroidx/cardview/widget/CardView;

    move-result-object v1

    invoke-static {v1, v0}, Le/a/b/b;->a(Landroid/view/View;Z)V

    .line 8
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->o1()Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;

    move-result-object v0

    invoke-virtual {v0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;->j()V

    .line 9
    :goto_3d
    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->z:Lf/n/g/f/c/f/c;

    invoke-virtual {v0, p1}, Lf/n/g/f/c/f/c;->A(Z)V

    return-void
.end method

.method public L0()I
    .registers 2

    .line 1
    sget v0, Lcom/junyue/novel/modules_index/R$layout;->activity_division:I

    return v0
.end method

.method public finish()V
    .registers 5

    .line 1
    sget-object v0, Lf/n/j/b;->u:Lf/n/j/b;

    const/4 v1, 0x1

    const/4 v2, 0x0

    const/4 v3, 0x2

    invoke-static {v0, v1, v2, v3, v2}, Lf/n/j/b;->u0(Lf/n/j/b;ZLi/a0/c/a;ILjava/lang/Object;)Z

    .line 2
    invoke-static {}, Lf/m/a/b;->a()Lf/m/a/a;

    move-result-object v0

    const-string v1, "UPDATE_BOOK_SHELF_GROUP"

    const-string v2, ""

    invoke-virtual {v0, v1, v2}, Lf/m/a/a;->h(Ljava/lang/String;Ljava/lang/Object;)V

    .line 3
    invoke-super {p0}, Landroid/app/Activity;->finish()V

    return-void
.end method

.method public final l1()Lf/n/g/f/c/f/c;
    .registers 2

    .line 1
    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->z:Lf/n/g/f/c/f/c;

    return-object v0
.end method

.method public final m1()Ljava/util/List;
    .registers 5
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "()",
            "Ljava/util/List<",
            "Lcom/junyue/novel/sharebean/reader/CollBookBean;",
            ">;"
        }
    .end annotation

    .line 1
    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->z:Lf/n/g/f/c/f/c;

    invoke-virtual {v0}, Le/a/b/h/b/e/a;->h()Ljava/util/List;

    move-result-object v0

    .line 2
    new-instance v1, Ljava/util/ArrayList;

    invoke-direct {v1}, Ljava/util/ArrayList;-><init>()V

    .line 3
    invoke-interface {v0}, Ljava/lang/Iterable;->iterator()Ljava/util/Iterator;

    move-result-object v0

    :cond_f
    :goto_f
    invoke-interface {v0}, Ljava/util/Iterator;->hasNext()Z

    move-result v2

    if-eqz v2, :cond_21

    invoke-interface {v0}, Ljava/util/Iterator;->next()Ljava/lang/Object;

    move-result-object v2

    instance-of v3, v2, Lcom/junyue/novel/sharebean/reader/CollBookBean;

    if-eqz v3, :cond_f

    invoke-interface {v1, v2}, Ljava/util/Collection;->add(Ljava/lang/Object;)Z

    goto :goto_f

    :cond_21
    return-object v1
.end method

.method public final n1()Landroid/widget/FrameLayout;
    .registers 2

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->p1()Landroidx/cardview/widget/CardView;

    move-result-object v0

    return-object v0
.end method

.method public final o1()Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->A:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$a;

    return-object v0
.end method

.method public onClick(Landroid/view/View;)V
    .registers 6

    if-eqz p1, :cond_b

    .line 1
    invoke-virtual {p1}, Landroid/view/View;->getId()I

    move-result v0

    invoke-static {v0}, Ljava/lang/Integer;->valueOf(I)Ljava/lang/Integer;

    move-result-object v0

    goto :goto_c

    :cond_b
    const/4 v0, 0x0

    .line 2
    :goto_c
    sget v1, Lcom/junyue/novel/modules_index/R$id;->iv_more:I

    if-nez v0, :cond_11

    goto :goto_3f

    :cond_11
    invoke-virtual {v0}, Ljava/lang/Integer;->intValue()I

    move-result v2

    if-ne v2, v1, :cond_3f

    .line 3
    new-instance v0, Lf/n/g/f/c/f/g/a;

    .line 4
    invoke-virtual {p0}, Lf/n/c/a/a;->getContext()Landroid/content/Context;

    move-result-object v1

    .line 5
    invoke-static {p1}, Lf/n/c/c0/y0;->f(Landroid/view/View;)Landroid/graphics/Rect;

    move-result-object p1

    iget p1, p1, Landroid/graphics/Rect;->bottom:I

    invoke-virtual {p0}, Lf/n/c/a/a;->getContext()Landroid/content/Context;

    move-result-object v2

    const/high16 v3, 0x40000000  # 2.0f

    invoke-static {v2, v3}, Lf/n/c/c0/m;->e(Landroid/content/Context;F)I

    move-result v2

    add-int/2addr p1, v2

    new-instance v2, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$g;

    invoke-direct {v2, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$g;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    .line 6
    new-instance v3, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$h;

    invoke-direct {v3, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$h;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    .line 7
    invoke-direct {v0, v1, p1, v2, v3}, Lf/n/g/f/c/f/g/a;-><init>(Landroid/content/Context;ILi/a0/c/l;Li/a0/c/l;)V

    .line 8
    invoke-virtual {v0}, Lf/n/g/f/c/f/g/a;->show()V

    goto :goto_4e

    .line 9
    :cond_3f
    :goto_3f
    sget p1, Lcom/junyue/novel/modules_index/R$id;->tv_cancel:I

    if-nez v0, :cond_44

    goto :goto_4e

    :cond_44
    invoke-virtual {v0}, Ljava/lang/Integer;->intValue()I

    move-result v0

    if-ne v0, p1, :cond_4e

    const/4 p1, 0x0

    .line 10
    invoke-virtual {p0, p1}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->B1(Z)V

    :cond_4e
    :goto_4e
    return-void
.end method

.method public onCreate(Landroid/os/Bundle;)V
    .registers 4

    .line 1
    invoke-super {p0, p1}, Lf/n/c/a/a;->onCreate(Landroid/os/Bundle;)V

    .line 2
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->u1()Landroidx/recyclerview/widget/RecyclerView;

    move-result-object p1

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->z:Lf/n/g/f/c/f/c;

    invoke-virtual {p1, v0}, Landroidx/recyclerview/widget/RecyclerView;->setAdapter(Landroidx/recyclerview/widget/RecyclerView$Adapter;)V

    .line 3
    invoke-static {p0}, Lf/n/g/f/c/f/a;->c(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    .line 4
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->v1()Ljava/lang/String;

    move-result-object p1

    const/4 v0, 0x0

    if-eqz p1, :cond_2a

    .line 5
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->w1()Lcom/junyue/novel/skin/skin2/widget/DefaultTitleBar;

    move-result-object p1

    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->v1()Ljava/lang/String;

    move-result-object v1

    invoke-virtual {p1, v1}, Lcom/junyue/novel/skin/skin2/widget/DefaultTitleBar;->setTitle(Ljava/lang/CharSequence;)V

    .line 6
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->t1()Landroid/view/View;

    move-result-object p1

    const/4 v1, 0x1

    invoke-static {p1, v1}, Le/a/b/b;->a(Landroid/view/View;Z)V

    goto :goto_31

    .line 7
    :cond_2a
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->t1()Landroid/view/View;

    move-result-object p1

    invoke-static {p1, v0}, Le/a/b/b;->a(Landroid/view/View;Z)V

    .line 8
    :goto_31
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->x1()V

    .line 9
    invoke-virtual {p0, v0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->B1(Z)V

    return-void
.end method

.method public final p1()Landroidx/cardview/widget/CardView;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->w:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Landroidx/cardview/widget/CardView;

    return-object v0
.end method

.method public final q1()Ljava/util/ArrayList;
    .registers 2
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "()",
            "Ljava/util/ArrayList<",
            "Ljava/lang/String;",
            ">;"
        }
    .end annotation

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->x:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Ljava/util/ArrayList;

    return-object v0
.end method

.method public final r1()Landroid/view/View;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->v:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Landroid/view/View;

    return-object v0
.end method

.method public final s1()Landroid/view/View;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->u:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Landroid/view/View;

    return-object v0
.end method

.method public final t1()Landroid/view/View;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->t:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Landroid/view/View;

    return-object v0
.end method

.method public final u1()Landroidx/recyclerview/widget/RecyclerView;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->s:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Landroidx/recyclerview/widget/RecyclerView;

    return-object v0
.end method

.method public final v1()Ljava/lang/String;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->y:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Ljava/lang/String;

    return-object v0
.end method

.method public final w1()Lcom/junyue/novel/skin/skin2/widget/DefaultTitleBar;
    .registers 2

    iget-object v0, p0, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->r:Li/d;

    invoke-interface {v0}, Li/d;->getValue()Ljava/lang/Object;

    move-result-object v0

    check-cast v0, Lcom/junyue/novel/skin/skin2/widget/DefaultTitleBar;

    return-object v0
.end method

.method public final x1()V
    .registers 2

    .line 1
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->s1()Landroid/view/View;

    move-result-object v0

    invoke-virtual {v0, p0}, Landroid/view/View;->setOnClickListener(Landroid/view/View$OnClickListener;)V

    .line 2
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->r1()Landroid/view/View;

    move-result-object v0

    invoke-virtual {v0, p0}, Landroid/view/View;->setOnClickListener(Landroid/view/View$OnClickListener;)V

    return-void
.end method

.method public final y1(Ljava/lang/Object;)V
    .registers 12

    .line 1
    instance-of v0, p1, Lf/n/g/f/c/f/b;

    if-eqz v0, :cond_8

    .line 2
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->z1()V

    goto :goto_35

    .line 3
    :cond_8
    instance-of v0, p1, Lcom/junyue/novel/sharebean/reader/BookshelfDirMapInner;

    if-eqz v0, :cond_35

    .line 4
    check-cast p1, Lcom/junyue/novel/sharebean/reader/BookshelfDirMapInner;

    invoke-virtual {p1}, Lcom/junyue/novel/sharebean/reader/BookshelfDirMapInner;->getTitle()Ljava/lang/String;

    move-result-object p1

    if-eqz p1, :cond_32

    invoke-static {}, Lf/n/g/f/c/f/a;->b()Lcom/junyue/novel/sharebean/reader/BookshelfDirMap;

    move-result-object v0

    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->q1()Ljava/util/ArrayList;

    move-result-object v1

    const-string v2, "mIds"

    invoke-static {v1, v2}, Li/a0/d/j;->d(Ljava/lang/Object;Ljava/lang/String;)V

    const/4 v3, 0x0

    const/4 v4, 0x0

    const/4 v5, 0x0

    const/4 v6, 0x0

    const/4 v7, 0x0

    const/16 v8, 0x3e

    const/4 v9, 0x0

    const-string v2, ","

    invoke-static/range {v1 .. v9}, Li/v/t;->N(Ljava/lang/Iterable;Ljava/lang/CharSequence;Ljava/lang/CharSequence;Ljava/lang/CharSequence;ILjava/lang/CharSequence;Li/a0/c/l;ILjava/lang/Object;)Ljava/lang/String;

    move-result-object v1

    invoke-virtual {v0, p1, v1}, Lcom/junyue/novel/sharebean/reader/BookshelfDirMap;->insertToDir(Ljava/lang/String;Ljava/lang/String;)V

    .line 5
    :cond_32
    invoke-virtual {p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;->finish()V

    :cond_35
    :goto_35
    return-void
.end method

.method public final z1()V
    .registers 9

    .line 1
    sget-object v5, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$i;->a:Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$i;

    .line 2
    new-instance v6, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$j;

    invoke-direct {v6, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$j;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    .line 3
    new-instance v7, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$k;

    invoke-direct {v7, p0}, Lcom/junyue/novel/modules/index/ui/BookDivisionActivity$k;-><init>(Lcom/junyue/novel/modules/index/ui/BookDivisionActivity;)V

    const-string v1, ""

    const-string v2, ""

    const-string v3, "取消"

    const-string v4, "创建并移动"

    move-object v0, p0

    .line 4
    invoke-static/range {v0 .. v7}, Lf/n/g/f/c/f/g/c;->a(Landroid/app/Activity;Ljava/lang/String;Ljava/lang/String;Ljava/lang/String;Ljava/lang/String;Li/a0/c/a;Li/a0/c/a;Li/a0/c/a;)Lf/n/g/f/c/f/g/d;

    move-result-object v0

    .line 5
    invoke-virtual {v0}, Landroid/app/Dialog;->show()V

    return-void
.end method
