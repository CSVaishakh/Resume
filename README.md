# LaTeX Resume

This repository contains the LaTeX source code and compiled PDF of my professional resume.

## Repository Structure

*   [Resume.tex](./Resume.tex): The LaTeX source file containing the resume content, layout, and formatting.
*   [latexmkrc](./latexmkrc): Configuration for `latexmk` to build the document and output artifacts to the `out/` directory.
*   `out/`: Directory containing compilation outputs.
    *   `out/Resume.pdf`: The final compiled, ATS-friendly PDF resume (tracked in Git).
    *   Other auxiliary build files (ignored by Git).

## Compilation Instructions

To build the resume from source, you need a LaTeX distribution (such as TeX Live, MacTeX, or MiKTeX) installed.

### Using `latexmk` (Recommended)

This project is configured with `latexmk` to automatically output build files to the `out/` directory. Run the following command in the repository root:

```bash
latexmk -pdf Resume.tex
```

This will compile the LaTeX source and generate/update `out/Resume.pdf`.

### Using `pdflatex`

If you do not have `latexmk` installed, you can compile directly using `pdflatex` (make sure the `out` directory exists first):

```bash
mkdir -p out
pdflatex -output-directory=out Resume.tex
```

## Resume Summary

*   **Name:** C S Vaishakh
*   **Education:** B.Tech in Artificial Intelligence and Data Science at St. Joseph's College of Engineering and Technology, Palai (2023 -- 2027)
*   **Core Technical Skills:**
    *   **Programming:** Python, TypeScript, Go, Java, JavaScript
    *   **Web & Backend:** Next.js, React, Express.js, Fiber v3, FastAPI, Node.js, TanStack Start, REST APIs
    *   **Databases & ORMs:** PostgreSQL, MongoDB, GORM, Drizzle ORM, Mongoose
    *   **AI / ML:** TensorFlow.js, Feature Engineering, Model Evaluation, Scikit-learn, NumPy, Pandas
    *   **Tools:** Git, GitHub Actions, Docker, Turborepo, Bun, Postman, Linux
