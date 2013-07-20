+ Welcome
This is small CUDA mode for emacs tooked from emacswiki
http://www.emacswiki.org/emacs/CudaMode and enhanced a bit.

+ Quick setup
Just paste this snippet into your config

``
(autoload 'cuda-mode "cuda-mode" nil t)
(add-to-list 'auto-mode-alist '("\\.cuh?\\'" . cuda-mode))
``

