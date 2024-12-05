Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 02:00:37 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/hardikdagar7/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_01:58:04] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_01:58:06] STEP 2: Create topics started

  [INFO 2024-12-05_01:58:18] STEP 2: Completed

  [INFO 2024-12-05_01:58:23] STEP 3: producing data started

  [INFO 2024-12-05_01:58:25] STEP 4: Preprocessing started

  [INFO 2024-12-05_01:58:25] MQTT connection established...

  [INFO 2024-12-05_01:58:27] STEP 4: Preprocessing started

  [INFO 2024-12-05_01:58:27] STEP 7: Visualization started

  [INFO 2024-12-05_01:58:33] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_01:58:41] STEP 8: Starting docker push for: hardikdagar0207/abc-7042-amd64

  [INFO 2024-12-05_01:58:46] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_01:58:51] STEP 9: Starting privateGPT

  [INFO 2024-12-05_01:59:01] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_01:59:06] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 784355a77a86 hardikdagar0207/abc-7042-amd64 - message=0

  [INFO 2024-12-05_02:00:32] STEP 8: Successfully ran Docker push: docker push hardikdagar0207/abc-7042-amd64 - message=0

  [INFO 2024-12-05_02:00:37] STEP 10: Started to build the documentation

  [INFO 2024-12-05_02:00:38] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


