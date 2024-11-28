Latest Logs From Latest Build
==============================

Generated On: 2024-11-28 18:18:56 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/carterd132/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-28_18:17:13] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-28_18:17:16] STEP 2: Create topics started

  [INFO 2024-11-28_18:17:31] STEP 2: Completed

  [INFO 2024-11-28_18:17:39] STEP 3: producing data started

  [INFO 2024-11-28_18:17:41] MQTT connection established...

  [INFO 2024-11-28_18:17:41] STEP 4: Preprocessing started

  [INFO 2024-11-28_18:17:43] STEP 4: Preprocessing started

  [INFO 2024-11-28_18:17:44] STEP 7: Visualization started

  [INFO 2024-11-28_18:17:50] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-28_18:18:04] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-11-28_18:18:04] STEP 8: Starting docker push for: carterd132@gmail.com/cybersecuritywithprivategpt-28fb-amd64

  [INFO 2024-11-28_18:18:09] STEP 9: Starting privateGPT

  [WARN 2024-11-28_18:18:24] STEP 8: There seems to be an issue creating the container.  Here is the commit command: docker commit 941e737f8dc9 carterd132@gmail.com/cybersecuritywithprivategpt-28fb-amd64 - message=1.  Container may NOT pushed.

  [INFO 2024-11-28_18:18:29] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [WARN 2024-11-28_18:18:48] STEP 8: There may be an issue pushing to Docker Hub, or just wait few seconds to see if the container shows up.  Here is the command: docker push carterd132@gmail.com/cybersecuritywithprivategpt-28fb-amd64 - message=1

  [INFO 2024-11-28_18:18:55] STEP 10: Started to build the documentation

  [INFO 2024-11-28_18:18:57] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


