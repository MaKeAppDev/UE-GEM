cmake_minimum_required(VERSION 2.8)

project(GELM_Uebungen NONE)
include(UseLATEX)

add_latex_document(uebung1.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung2.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung3.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung4.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung5.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung6.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung7.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung8.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung9.tex DEFAULT_PDF MANGLE_TARGET_NAMES)
add_latex_document(uebung11.tex DEFAULT_PDF MANGLE_TARGET_NAMES)


add_custom_target(pdf)
add_dependencies(pdf uebung1_pdf uebung2_pdf uebung3_pdf uebung4_pdf uebung5_pdf uebung6_pdf uebung7_pdf uebung8_pdf uebung9_pdf uebung11_pdf)