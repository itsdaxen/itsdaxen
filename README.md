# Farzam Daghighi

Computer Science & Engineering student at the University of Oulu, specializing in Computer Engineering. Focused on systems software and hardware–software integration, with interests in embedded systems and edge AI. Seeking trainee opportunities in Finland and the Nordics.

[daghighi.dev](https://daghighi.dev) · [Email](mailto:farzam.sadegh@gmail.com)

## Embedded systems

- **[nRF52840 DK / Zephyr](https://github.com/itsdaxen/nrf52840-zephyr):** Hands-on firmware learning and hardware testing with nRF Connect SDK. Built and flashed Zephyr samples, configured a BME280 over I2C, and verified live temperature, pressure and humidity readings over serial. Used multimeter voltage and continuity measurements for USB power-path troubleshooting.

- **[Pico W / FreeRTOS](https://github.com/itsdaxen/pico-freertos):** Configured the Pico SDK and FreeRTOS environment on macOS and ran the course-provided JTKJ HAT example with separate tasks for LED control, an OLED counter and buzzer output. Documents the tested setup and runtime behavior.

## Native software and upstream contributions

- **[WardView](https://github.com/itsdaxen/WardView)**: Bedside patient-monitor UI prototype built with Qt Quick, QML, C++17, and CMake. Includes C++ alarm and trend models, editable alarm acknowledgement, and responsive navigation. Uses demo data.
- **[Qt Advanced Docking System #862](https://github.com/githubuser0xFFFF/Qt-Advanced-Docking-System/pull/862)**: Merged C++ fix that saves the focused dock widget in layout state and restores its focus after loading the layout.

## Python and machine learning

- **[TwinTag Backend](https://github.com/itsdaxen/twintag-backend)**: Co-built at JunctionX Vaasa for VEO360, including expanding four ABB REX615 reference views into 10,000 labeled images through background compositing and augmentation, training a YOLO11m detector, and running it on real scan imagery. On 108 real scan images, retained 38 detections at ≥85% confidence and fused them into seven asset tags using E57-based 3D localization, with pretrained Qwen3-VL context extraction. Demonstrated on one device type, with a reference-image-to-training workflow that can be reused for other devices. [Frontend](https://github.com/itsdaxen/twintag-frontend)
- **[LLM Internals Lab](https://github.com/itsdaxen/llm-internals-lab)**: Python/PyTorch learning project: tokenization, vocabulary construction and GPT-style next-token sampling on `main`; token/positional embeddings and trainable self-attention on the public [attention branch](https://github.com/itsdaxen/llm-internals-lab/tree/feature/attention), with component tests. Pretraining, fine-tuning and profiling remain future work.

## Product projects

- **[Recruina](https://github.com/itsdaxen/recruina-casestudy)**: Recruitment platform tested with 30+ users over two months. PostgreSQL/Prisma, background jobs, private storage, CV parsing, Docker/Caddy. [Demo](https://recruina.vercel.app)
- **[iMeal](https://imealv2.vercel.app)**: AI meal planning and groceries with Next.js, TypeScript, and Supabase.

## More open source

- **[IPython #15348](https://github.com/ipython/ipython/pull/15348)**: Restored `pathlib.Path` support in `IFrame`, preserving HTML escaping; added regression coverage.
