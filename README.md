# nguyen
#lang racket  (require (planet dvanhorn/fector:1:1))  (require "bloom-filter.rkt")  ;; Insert elements  (define *BF* (make-bloom-filter 5 100 10 (lambda (x) 1) (make-fector 7 #f)))
