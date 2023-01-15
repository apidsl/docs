STREAM

commmand:
+ map()
+ stream()
+ findFirst()

https://github.com/bakdata/streams-bootstrap


https://github.com/bakdata/kserve-client

    
    return new KServeRequester<InferenceRequest<TextToTranslate>, TranslatorResponse>()
    .requestInferenceService(InferenceRequest.<TextToTranslate>builder()
    .inputs(List.of(
    RequestInput.<TextToTranslate>builder()
    .name("Translation")
    .datatype("BYTES")
    .shape(List.of(1))
    .datatype("BYTES")
    .parameters(Parameters.builder()
    .contentType("str")
    .build())
    .data(input)
    .build()
    ))
    .build())
    .map(InferenceResponse::getOutputs)
    .stream()
    .flatMap(Collection::stream)
    .map(ResponseOutput::getData)
    .findFirst()
    .orElseThrow();
