# SE3082 Lab 10: CUDA Programming

**Module:** SE3082 – Parallel Computing  
**Lab:** 10 – CUDA (Google Colab Edition)

## Description

This lab explores GPU programming with CUDA in Google Colab. It covers GPU execution timing, CUDA error handling, picture scaling using a 2D grid, and element-wise multiplication using a 3D grid.

## Exercises

1. **Timing a GPU Program**
2. **Catching Errors with the `CHECK()` Macro**
3. **Scaling a Picture with a 2D Grid**
4. **Element-wise Multiplication Using a 3D Grid**

## Tools Used

- Google Colab
- NVIDIA CUDA Toolkit
- CUDA C/C++

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Enable a GPU runtime, if available, through **Runtime → Change runtime type → T4 GPU** (or another available GPU).
3. Run the notebook cells in order.
4. Review the timing measurements, error-handling experiments, and verification outputs for each exercise.

> **Note:** CUDA code requires a compatible NVIDIA GPU runtime and CUDA environment. Available hardware and runtime options may vary in Google Colab.

## Verification

The lab includes:

- GPU program timing measurements.
- CUDA error-handling experiments using the `CHECK()` macro.
- Result checks for picture scaling and element-wise multiplication.
- Comparisons between computed results and expected results, where implemented in the notebook.

## Submission

**Completed lab notebook:** `SE3082_Lab10_IT24103581.ipynb`
