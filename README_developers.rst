
To see test errors after a test:

.. code-block:: console

    pyb clean run_unit_tests || cat target/reports/TEST*xml

and

.. code-block:: console

    pyb run_cram_tests || less /home/robert/ss/afp-cli/target/reports/cram.err
