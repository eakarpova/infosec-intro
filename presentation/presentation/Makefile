# Основные настройки
SRC = presentation.md
FILES += $(patsubst %.md, %.pdf, $(wildcard *.md))
FILES += $(patsubst %.md, %.html, $(wildcard *.md))

# Фильтры и обработка
FILTERS = --citeproc
# FILTERS += -F pandoc-crossref  # Раскомментируйте при необходимости

# Настройки PDF
PDF_ENGINE = --pdf-engine=lulatex  # Используем xelatex для лучшей поддержки шрифтов
PDF_OPTIONS = --number-sections \
              -V mainfont="DejaVu Sans" \
              -V sansfont="DejaVu Sans" \
              -V monofont="DejaVu Sans Mono" \
              -V fontsize=11pt \
              -V classoption=aspectratio=169 \
              --variable=fonts=system

# Форматные опции для презентаций
PDF_FORMAT_OPTIONS = -t beamer --slide-level=2

# Настройки HTML
REVEALJS_THEME = beige

# Правила сборки
%.pdf: %.md
	@pandoc "$<" $(FILTERS) $(PDF_ENGINE) $(PDF_OPTIONS) $(PDF_FORMAT_OPTIONS) -o "$@" || (echo "Ошибка сборки PDF"; exit 1)

%.html: %.md
	@pandoc "$<" --embed-resources --standalone -t revealjs -V theme=$(REVEALJS_THEME) -o "$@"

# Цели
all: $(FILES)

clean:
	@rm -f $(FILES) *~

.PHONY: all clean
