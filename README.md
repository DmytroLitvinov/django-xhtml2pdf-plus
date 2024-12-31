Django xhtml2pdf plus ⏩
=====================================

**🚀 This is updated version of [django-xhtml2pdf](https://github.com/xhtml2pdf/django-xhtml2pdf).**

`django-xhtml2pdf-plus` is a Django app to render Django templates as PDF files.

To keep Django ecosystem fresh and updated, please share your love and support, click `Star` 🫶


# Install:

Install the package via pip:

```bash
pip install django-xhtml2pdf-plus
```

# Usage:

```python
# Import PDFView in your views.py

from django_xhtml2pdf_plus.views import PDFView

class MyPDFView(PDFView):
    template_name = 'my_template.html'
    filename = 'my_pdf.pdf'
```
