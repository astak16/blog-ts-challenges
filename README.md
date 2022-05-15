> Create by 草叔 2022-03-27

在工作中很多时候停留在会用的阶段，对类型定义文件看不懂，就想提升自己的 `ts` 水平，在 github 中找到了 [ts类型体操](https://github.com/type-challenges/type-challenges) 这个项目，在里面看到一个大神的文章： [TypeScript 类型体操天花板，用类型运算写一个 Lisp 解释器](https://zhuanlan.zhihu.com/p/427309936) 后，对 `ts` 有了全新的认识，比如文章里提到的用 `ts` 实现四则运算，对现阶段的我来说太震撼了，准备好好学一学 `ts`，开此项目记录自己 `ts` 的学习笔记。

## 题目

1. [MyPick](https://github.com/astak16/blog-ts-challenges/issues/3) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
2. [MyOmit](https://github.com/astak16/blog-ts-challenges/issues/4) <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/>
3. [MyExclude](https://github.com/astak16/blog-ts-challenges/issues/5) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
4. [FirstOfArray](https://github.com/astak16/blog-ts-challenges/issues/7) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
5. [MyReadonly](https://github.com/astak16/blog-ts-challenges/issues/9) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
6. [MyReturnType](https://github.com/astak16/blog-ts-challenges/issues/11) <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/>
7. [GetRequired](https://github.com/astak16/blog-ts-challenges/issues/12) <img src="https://img.shields.io/badge/-hard-de3d37" alt="hard"/>
8. [GetOptional](https://github.com/astak16/blog-ts-challenges/issues/13) <img src="https://img.shields.io/badge/-hard-de3d37" alt="hard"/>
9. [MyAwaited](https://github.com/astak16/blog-ts-challenges/issues/14) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
10. [If](https://github.com/astak16/blog-ts-challenges/issues/15) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
11. [Concat](https://github.com/astak16/blog-ts-challenges/issues/16) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
12. [MyReadonly2](https://github.com/astak16/blog-ts-challenges/issues/17) <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/>
13. [DeepReadonly](https://github.com/astak16/blog-ts-challenges/issues/19) <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/>
14. [TupleToUnion](https://github.com/astak16/blog-ts-challenges/issues/20) <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/>
15. [TupleToObject](https://github.com/astak16/blog-ts-challenges/issues/21) <img src="https://img.shields.io/badge/-easy-7aad0c" alt="easy"/>
16. [UnionToTuple](https://github.com/astak16/blog-ts-challenges/issues/23) <img src="https://img.shields.io/badge/-hard-de3d37" alt="hard"/>

## 基础知识
1. [不理解到理解 - `as`](https://github.com/astak16/blog-ts-challenges/issues/18#issue-1225525854)
2. [不理解到理解 - `-?`和`+?`](https://github.com/astak16/blog-ts-challenges/issues/18#issuecomment-1117469364)
3. [条件类型：extends 用法](https://github.com/astak16/blog-ts-challenges/issues/1)
4. [Pick](https://github.com/astak16/blog-ts-challenges/issues/2#issuecomment-1079862389)
5. [Exclude](https://github.com/astak16/blog-ts-challenges/issues/2#issuecomment-1079876517)
6. [Omit](https://github.com/astak16/blog-ts-challenges/issues/2#issuecomment-1084434376)
7. [Omit、Pick、Exclude 的区别](https://github.com/astak16/blog-ts-challenges/issues/2#issuecomment-1084480379)
8. [ReturnType](https://github.com/astak16/blog-ts-challenges/issues/2#issuecomment-1111139104)
9. [通俗易懂的讲解 infer 关键字](https://github.com/astak16/blog-ts-challenges/issues/6)
10. [默认约束 = keyof T](https://github.com/astak16/blog-ts-challenges/issues/8)
11. [keyof 和类型访问](https://github.com/astak16/blog-ts-challenges/issues/10)
12. [协变和逆变](https://github.com/astak16/blog-ts-challenges/issues/22)

## 参考文章
1. [TupleToUnion](https://github.com/astak16/blog-ts-challenges/issues/20) ---- [TypeScript: How to get types from arrays](https://steveholgado.com/typescript-types-from-arrays/)
2. [协变和逆变](https://github.com/astak16/blog-ts-challenges/issues/22) ---- [大白话聊 TypeScript 中的变型](https://no1.engineer/articles/2021-03/covariance-and-contravariance)
