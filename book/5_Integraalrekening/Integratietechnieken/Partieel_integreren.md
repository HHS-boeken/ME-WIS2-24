from manim import *

class PartieelIntegrerenPremium(Scene):
    def construct(self):

        # =========================
        # KLEUREN
        # =========================

        BG = "#111111"
        TEXT = "#F5F5F5"
        BLUE_U = "#4FC3F7"
        GREEN_DV = "#81C784"
        YELLOW_ANSWER = "#FFD54F"

        self.camera.background_color = BG

        # =========================
        # TITEL
        # =========================

        title = Text(
            "Voorbeeld 1 — Partieel integreren",
            font_size=34,
            color=TEXT
        )

        title.to_corner(UL).shift(RIGHT * 0.4 + DOWN * 0.3)

        self.play(Write(title), run_time=2)

        # =========================
        # OPGAVE
        # =========================

        opgave_text = Text(
            "Bereken de onbepaalde integraal:",
            font_size=28,
            color=GRAY_B
        )

        opgave = MathTex(
            r"\int (2x+3)\cos(x)\,dx",
            font_size=42,
            color=TEXT
        )

        opgave_group = VGroup(opgave_text, opgave)
        opgave_group.arrange(DOWN, aligned_edge=LEFT, buff=0.35)

        opgave_group.next_to(title, DOWN, aligned_edge=LEFT, buff=0.9)

        self.play(Write(opgave_text), run_time=1.5)
        self.play(Write(opgave), run_time=2)

        self.wait(1)

        # =========================
        # STAP 1
        # =========================

        stap1 = Text(
            "Stap 1 — Kies u en dv",
            font_size=30,
            color=GRAY_A
        )

        stap1.next_to(opgave_group, DOWN, aligned_edge=LEFT, buff=1.0)

        keuze = MathTex(
            r"u = 2x+3",
            r"\qquad",
            r"dv = \cos(x)\,dx",
            font_size=40
        )

        keuze[0].set_color(BLUE_U)
        keuze[2].set_color(GREEN_DV)

        keuze.next_to(stap1, DOWN, aligned_edge=LEFT, buff=0.45)

        self.play(Write(stap1), run_time=1.5)
        self.play(Write(keuze), run_time=2.5)

        self.wait(2)

        self.play(
            FadeOut(stap1),
            FadeOut(keuze),
            run_time=1
        )

        # =========================
        # STAP 2
        # =========================

        stap2 = Text(
            "Stap 2 — Bepaal du",
            font_size=30,
            color=GRAY_A
        )

        stap2.next_to(opgave_group, DOWN, aligned_edge=LEFT, buff=1.0)

        du = MathTex(
            r"\frac{du}{dx} = 2",
            r"\\",
            r"du = 2\,dx",
            font_size=40
        )

        du.set_color(BLUE_U)

        du.next_to(stap2, DOWN, aligned_edge=LEFT, buff=0.45)

        self.play(Write(stap2), run_time=1.5)
        self.play(Write(du), run_time=2.5)

        self.wait(2)

        self.play(
            FadeOut(stap2),
            FadeOut(du),
            run_time=1
        )

        # =========================
        # STAP 3
        # =========================

        stap3 = Text(
            "Stap 3 — Bepaal v",
            font_size=30,
            color=GRAY_A
        )

        stap3.next_to(opgave_group, DOWN, aligned_edge=LEFT, buff=1.0)

        vgroep = MathTex(
            r"dv = \cos(x)\,dx",
            r"\\",
            r"v = \sin(x)",
            font_size=40
        )

        vgroep.set_color(GREEN_DV)

        vgroep.next_to(stap3, DOWN, aligned_edge=LEFT, buff=0.45)

        self.play(Write(stap3), run_time=1.5)
        self.play(Write(vgroep), run_time=2.5)

        self.wait(2)

        self.play(
            FadeOut(stap3),
            FadeOut(vgroep),
            run_time=1
        )

        # =========================
        # STAP 4
        # =========================

        stap4 = Text(
            "Stap 4 — Pas partieel integreren toe",
            font_size=30,
            color=GRAY_A
        )

        stap4.next_to(opgave_group, DOWN, aligned_edge=LEFT, buff=1.0)

        uitwerking1 = MathTex(
            r"\int u\,dv = uv - \int v\,du",
            font_size=38
        )

        uitwerking2 = MathTex(
            r"= (2x+3)\sin(x) - \int \sin(x)\cdot 2\,dx",
            font_size=38
        )

        uitwerking3 = MathTex(
            r"= (2x+3)\sin(x) - 2\int \sin(x)\,dx",
            font_size=38
        )

        uitwerking4 = MathTex(
            r"= (2x+3)\sin(x) + 2\cos(x) + C",
            font_size=40
        )

        uitwerking4.set_color(YELLOW_ANSWER)

        uitwerking_group = VGroup(
            uitwerking1,
            uitwerking2,
            uitwerking3,
            uitwerking4
        )

        uitwerking_group.arrange(
            DOWN,
            aligned_edge=LEFT,
            buff=0.45
        )

        uitwerking_group.next_to(
            stap4,
            DOWN,
            aligned_edge=LEFT,
            buff=0.5
        )

        self.play(Write(stap4), run_time=1.5)

        self.play(Write(uitwerking1), run_time=2)
        self.wait(1)

        self.play(Write(uitwerking2), run_time=2)
        self.wait(1)

        self.play(Write(uitwerking3), run_time=2)
        self.wait(1)

        self.play(Write(uitwerking4), run_time=2.5)

        self.wait(2)

        # =========================
        # ANTWOORD BOX
        # =========================

        box = SurroundingRectangle(
            uitwerking4,
            color=YELLOW_ANSWER,
            buff=0.25
        )

        self.play(Create(box), run_time=1.5)

        self.wait(3)