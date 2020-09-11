### REPOSITORIO ORIGINAL: https://github.com/vaieverton/Comic-Book-Translator ###

Já imaginou ter uma HQ em QUALQUER IDIOMA e poder traduzir capitulos inteiros em apenas UMA compilação?
No meu projeto é possível.

Guia para compilar e traduzir a HQ:

Clonar o código/repositório disponível no github
pip install opencv-python

pip install numpy

pip install unidecode

pip install tesseract

pip install googletrans

Instalar o Tesseract OCR na sua máquina:

Linux | Windows
Criar uma pasta contendo as páginas da HQ em formato .png ou .jpg,
formatas no seguinte formato: "nome_da_hq_{`NUMERO DA PAGE´}" (1,2,3,4...n)

Na linha 43 do código, inserir o numero da ultima página a ser traduzida

Na linha 48 do código, altere o caminho até suas imagens:
img = cv.imread('/caminho/nome_hq_page_'+num+'.jpg')

Execute o programa e aguarde até que todas as páginas sejam finalizadas
