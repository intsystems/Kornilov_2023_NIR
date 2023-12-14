|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Относительный шум в промежуточных градиентных методах
    :Тип научной работы: НИР
    :Автор: Никита Максимович Корнилов
    :Научный руководитель: д.ф.-м.н.  Гасников Александр Владимирович
  

Abstract
========

This project is devoted to first-order algorithms for smooth convex optimization with inexact gradients. Unlike the majority of the literature on this topic, we consider the setting of relative rather than absolute inexactness. More precisely, we assume that an additive error in the gradient is proportional to the gradient norm, rather than being globally bounded by some small quantity. We propose a novel analysis of the accelerated gradient method under relative inexactness and strong convexity and improve the bound on the maximum admissible error that preserves the linear convergence of the algorithm. In other words, we analyze how robust is the accelerated gradient method to the relative inexactness of the gradient information. Moreover, based on the Performance Estimation Problem (PEP) technique, we show that the obtained result is optimal for the family of accelerated algorithms we consider.

Research publications
===============================
1. Результаты представлены как часть статьи
    
    Kornilov, N., Gorbunov, E., Alkousa, M., Stonyakin, F., Dvurechensky, P., & Gasnikov, A. (2023). Intermediate Gradient Methods with Relative Inexactness. arXiv preprint arXiv:2310.00506.

    https://arxiv.org/pdf/2310.00506.pdf


Software modules developed as part of the study
======================================================
В папке `code` представлен  notebook  `code\Numerical_exp_ISTM.ipynb` для проведения эксппериментов с PEP. Для лучших результатов может потребоваться оптимизатор MOSEK. 
