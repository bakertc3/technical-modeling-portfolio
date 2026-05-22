# Applied Linear Algebra: Network Flow and Image Compression

## Overview

This project is another favorite of mine, and linear algebra was my favorite math course. I applied linear algebra methods to two different modeling problems: network flow analysis and image compression.

The first part modeled a network as a system of linear equations and used matrix methods to solve for unknown flow values. The second part used singular value decomposition to construct low-rank approximations of an image and evaluate the tradeoff between compression and reconstruction error.

This public version summarizes the modeling approach and selected conclusions while omitting course specific prompts, assignment structure, and full solution code. - Tom

## Tools and Methods

- MATLAB
- Systems of linear equations
- Matrix representation
- Row reduction
- LU decomposition
- Matrix inverses
- Cramer’s Rule
- Singular value decomposition
- Rank-k approximation
- Image compression
- RMSE evaluation

## Modeling Approach

The network flow portion of the project represented relationships among routers or nodes as a system of linear equations. The system was written in matrix form and solved using several linear algebra techniques, including row reduction, LU decomposition, inverse matrices, and Cramer’s Rule.

The image compression portion used singular value decomposition to approximate an image matrix using a reduced number of singular values. By comparing rank-k approximations, the project evaluated how much information could be preserved while reducing the amount of data needed to represent the image.

## Selected Visual

![SVD image compression comparison](figures/svd-image-compression-comparison.png)

## Selected Result

This visualization compares the original image with several SVD based rank-k approximations. As the compression ratio increases, fewer singular values are retained, which reduces the amount of information needed to represent the image but also produces greater visual distortion.

I included this comparison because it demonstrates an important modeling tradeoff: higher compression improves efficiency, but lower rank approximations preserve less detail. This connects directly to engineering analysis because model simplicity, storage efficiency, and accuracy must often be balanced against one another.

## Key Findings

The network flow model showed how a practical system can be translated into a matrix equation and solved using standard linear algebra tools. Different solution methods reached the same underlying result while emphasizing different computational ideas.

The SVD portion demonstrated that low rank approximations can preserve important visual structure while reducing dimensional complexity. Increasing the rank improves reconstruction quality but reduces the compression benefit.

The project emphasized the tradeoff between accuracy and efficiency, which is a central issue in modeling, engineering analysis, and systems design.

## Skills Demonstrated

- Translating a network problem into a system of linear equations
- Writing and solving matrix equations in MATLAB
- Applying row reduction, LU decomposition, matrix inverses, and Cramer’s Rule
- Using SVD to create rank-k approximations
- Evaluating approximation error using RMSE
- Interpreting compression versus accuracy tradeoffs
- Communicating mathematical results in an applied context

## Systems Engineering Connection

This project connects to systems engineering because it models relationships among connected components and evaluates tradeoffs between competing objectives.

The network flow portion reflects how system constraints can be represented mathematically. The image compression portion reflects how approximation, dimensionality reduction, and error analysis can support efficient system design and data representation.

## Tom's Academic Integrity Note

This page is a public facing project summary. Full assignment prompts, course specific materials, instructor-provided templates, and complete solution files are intentionally omitted.
