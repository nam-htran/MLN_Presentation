# AI & Human: A Dialectical Analysis

This is a single-page, scroll-based responsive website that explores the complex relationship between Artificial Intelligence and humanity through the lens of dialectical materialism. The project uses a narrative-driven approach, guiding the user through different facets of this relationship, from philosophical analysis to practical implications. It is built with Next.js, shadcn/ui, and Tailwind CSS, featuring various animations and interactive elements.

**Running demo on:**: [https://human-and-ai.vercel.app/](https://human-and-ai.vercel.app/)
<img width="1903" height="913" alt="{5E4750D4-40DC-4936-8B56-D37977964FAC}" src="https://github.com/user-attachments/assets/493468d8-5642-4bfd-ad6d-30b2c8192c05" />

## Features

-   **Full-Page Scrolling Experience:** The application is structured as a single-page website with distinct sections that snap into view as the user scrolls.
-   **Dynamic & Animated UI:** Utilizes Framer Motion and `tailwindcss-animate` for engaging animations, including parallax backgrounds and fade-in effects on scroll.
-   **Thematic Sections:**
    -   **Hero:** An introduction to the central question: "Partner or Competitor?".
    -   **Laws of Dialectics:** An interactive horizontal scroll section explaining the relationship through the laws of Contradiction, Quantity into Quality, and Negation of the Negation.
    -   **Examples:** Real-world examples of AI's impact on various sectors.
    -   **Ethics & Society:** A look into the ethical dilemmas posed by AI.
    -   **Future Skills:** Highlights the essential human skills in the age of AI.
    -   **Chatbot:** A mock chatbot interface to engage the user.
    -   **Conclusion:** A summary of the analysis and a call to action.
-   **Responsive Design:** The layout is fully responsive and adapts to different screen sizes.
-   **Dark Mode:** Built with dark mode by default, using `next-themes`.
-   **Dot Navigation:** A fixed navigation component on the side indicates the current section and allows for quick navigation.

## Technologies Used

-   **Framework:** [Next.js](https://nextjs.org/) 14 (App Router)
-   **UI Components:** [shadcn/ui](https://ui.shadcn.com/)
-   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
-   **Animation:** [Framer Motion](https://www.framer.com/motion/), [tailwindcss-animate](https://www.npmjs.com/package/tailwindcss-animate)
-   **Icons:** [Lucide React](https://lucide.dev/)
-   **Deployment:** [Vercel](https://vercel.com/)

## Project Structure

The project follows the standard Next.js App Router structure.
```
/
├── app/
│ ├── globals.css # Global styles and Tailwind directives
│ ├── layout.tsx # Root layout
│ └── page.tsx # Main page component
├── components/
│ ├── ui/ # Reusable UI components from shadcn/ui
│ ├── *.tsx # Section-specific components
│ ├── theme-provider.tsx
│ └── theme-toggle.tsx
├── lib/
│ └── utils.ts # Utility functions (e.g., cn)
├── public/ # Static assets (images, etc.)
└── ... # Configuration files
```
## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js (version 18 or higher) and a package manager (npm, yarn, or pnpm) installed on your system.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/nam-htran/MLN_Presentation
    cd MLN_Presentation
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```
    or
    ```bash
    yarn install
    ```
    or
    ```bash
    pnpm install
    ```

### Running the Development Server

To start the development server, run the following command:

```bash
npm run dev
```
Access to: localhost:3000 to running demo
```
localhost:3000
```
